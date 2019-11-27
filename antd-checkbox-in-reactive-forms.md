# 在响应式表单中使用 [ng-zorro-antd](https://ng.ant.design/docs/introduce/zh) 的 checkbox 组件

官方示例中，提供了两种checkbox使用方式，一种是在响应式表单中，绑定到单值上：

![remember](https://i.loli.net/2019/11/27/kp89AKLEjnlxY1o.png)

```html
<label nz-checkbox formControlName="remember">
  <span>Remember me</span>
</label>
```

```js
 this.validateForm = this.fb.group({
   userName: [null, [Validators.required]],
   password: [null, [Validators.required]],
   remember: [true]
 });
```

这种方式只能将单个布尔类型的值绑定到字段上。

如果有多个 checkbox ，则需要使用 `nz-checkbox-group` 组件，官方示例如下：

```html
<nz-checkbox-group [(ngModel)]="checkOptionsOne"></nz-checkbox-group>
```

``` js
checkOptionsOne = [
    { label: 'Apple', value: 'Apple', checked: true },
    { label: 'Pear', value: 'Pear', checked: false },
    { label: 'Orange', value: 'Orange', checked: false }
  ];
```

示例中是用 `ngModel` 直接进行双向绑定，如果直接应用在响应式表单（reactive-forms）中，会出现以下错误提示：

```
ngModel cannot be used to register form controls with a parent formGroup directive.  Try using formGroup's partner directive "formControlName" instead.
Or, if you'd like to avoid registering this form control, indicate that it's standalone in ngModelOptions.
```

需要添加 `[ngModelOptions]="{standalone: true}"` 配置。这种绑定方式，直接将选中状态保存在原选项数组中，在实际项目场景中，通常需要将选中的 value 合并成以逗号分隔的字符串。

这里的实现思路是每次 checkbox 选择后，调用 `ngModelChange` 方法合并选中的值，然后利用 `patchValue()` 方法将合并后的值更新到 form 对象中。当要修改包含多个控件的 FormGroup 的值时，使用 `patchValue()` 方法可以只更新模型对象中的一部分数据。

代码如下：

``` html
<form [formGroup]="form" nz-form>
  <nz-form-item>
      <nz-form-label [nzSpan]="6" [nzFor]="checkboxGroup">{{label}}</nz-form-label>
      <nz-form-control id="checkboxGroup">
          <nz-checkbox-group [(ngModel)]="question.opts" [ngModelOptions]="{standalone: true}" (ngModelChange)="changeCheckbox()"></nz-checkbox-group>
      </nz-form-control>
   </nz-form-item>
</form>
```

``` js
export class CheckboxTestComponent implements OnInit {

  form: FormGroup = new FormGroup({
    hobby: new FormControl('', [Validators.required])
  });

  options = [
    {value: 'code', label: '写代码', checked: false},
    {value: 'read', label: '阅读', checked: false},
    {value: 'game', label: '打游戏', checked: false},
  ];

  changeCheckbox() {
    const selectedValues = [];
    this.options.forEach(opt => {
      if (opt.checked) {
        selectedValues.push(opt.value);
      }
    });
    this.form.controls.hobby.patchValue(selectedValues.join(','));
  }

  ngOnInit(): void {
  }

  onSubmit(){
    console.log(this.form.value);
  }

}
```

运行效果如下：

![UTOOLS1574871795875.png](https://i.loli.net/2019/11/28/7UgiqcmI9knjZwE.png)



