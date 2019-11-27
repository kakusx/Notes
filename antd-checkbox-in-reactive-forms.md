# 在响应式表单中使用 [ng-zorro-antd](https://ng.ant.design/docs/introduce/zh) 的 checkbox 组件

官方示例中，提供了两种checkbox使用方式，一种是在响应式表单中，绑定到单值上

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







