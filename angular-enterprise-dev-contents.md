# 《Angular 企业级应用开发实战》目录

# 第1篇 准备

## 1. Angular概述

### 1.1 Angular产生的背景
1.1.1 Angular与 jQuery的不同
1.1.2 Angular与 React、 Vue. js优势对比
1.1.3 Angular、 React、Wes三者怎么选

### 1.2 学习 Angular需要什么基础
1.2.1 具备面向对象思维
1.2.2 熟悉常用的前端开发工具
1.2.3 具有一定的前端开发经验

### 1.3 如何使用本书
1.3.1 零基础的读者
1.3.2 有后端开发经验的读者
1.3.3 有前端开发经验的读者
1.3.4 有 Angular开发经验的读者

## 2. 实例1: 快速创建第一个 Angular应用

### 2.1 开发环境准备
2.1.1 安装 Node js和npm
2.1.2 设置npm镜像
2.1.3 选择合适的IDE
2.1.4 安装 Angular CLI

### 2.2 创建第一个应用—hello-world
2.2.1 使用 Angular CLI 初始化应用
2.2.2 运行 Angular应用

### 2.3 探索 Angular
2.3.1 src文件夹
2.3.2 根目录
2.3.3 npm包

### 2.4 配置 Type Script库



# 第2篇 入门

## 3. Type Script基础

### 3.1 了解 Type Script
3.1.1 Type Script与 JavaScript、 ECMAScript的关系
3.1.2 Type Script与 Angular的关系
3.1.3 使用 Type Script的优势
3.1.4 Type Script代码的编译及运行

### 3.2 变量与常量
3.2.1 var、let、 const三者的作用域
3.2.2 变量与常量的区别
3.2.3 什么是变量提升

### 3.3 Type Script的数据类型
3.3.1 基本类型
3.3.2 对象类型
3.3.3 任意类型
3.3.4 实例2:演示任意类型的使用
3.3.5 联合类型
3.3.6 交集类型

### 3.4 强大的面向对象体系
3.4.1 类
3.4.2 接囗
3.4.3 实例3:演示接囗的使用
3.4.4 泛型
3.4.5 实例4:演示泛型的使用
3.4.6 枚举

### 3.5 Type Script的命名空间
3.5.1 声明命名空间
3.5.2 实例5:声明命名空间
3.5.3 命名空间体
3.5.4 导入别名声明
3.5.5 实例6:导入别名声明
3.5.6 导出声明
3.5.7 合并声明
3.5.8 实例7:合并声明

### 3.6 Type Script的模块
3.6.1 了解模块
3.6.2 实例8:导入声明
3.6.3 实例9:导入 Require声明
3.6.4 实例10:导出声明
3.6.5 实例11:导出分配
3.6.6 了解 CommonJS模块
3.6.7 了解AMD模式

### 3.7 装饰器
3.7.1 定义装饰器
3.7.2 了解装饰器的执行时机
3.7.3 认识4类装饰器

## 4. 实例12:创建一个“用户管理应用

### 4.1 创建应用
4.1.1 新建“用户管理”应用
4.1.2 了解 Angular组件

### 4.2 修改 AppComponent组件
4.2.1 修改 app. component. ts文件
4.2.2 修改 app. component. htm文件
4.2.3 添加应用级别的样式

### 4.3 实现用户编辑器
4.3.1 创建用户列表组件
4.3.2 添加user属性
4.3.3 显示用户
4.3.4 显示users Component视图
4.3.5 创建user类
4.3.6 编辑用户信息
4.3.7 添加 Forms Module模块
4.3.8 声明组件

### 4.4 展示用户列表
4.4.1 添加用户列表数据
4.4.2 显示用户列表
4.4.3 用 *ngFor列出用户
4.4.4 添加样式
4.4.5 添加事件
4.4.6 设置选中的样式

### 4.5 多组件化开发
4.5.1 创建UserDetailComponent组件
4.5.2 编辑user-detail.component.htm文件
4.5.3 编辑user-detail.component.ts文件
4.5.4 编辑users.component.htm文件

### 4.6 使用服务
4.6.1 服务的好处
4.6.2 创建 UserService 服务
4.6.3 提供 UserService 服务
4.6.4 修改 UsersComponent 组件
4.6.5 使用 Observable 数据
4.6.6 显示消息

### 4.7 使用路由
4.7.1 路由的用处
4.7.2 创建 AppRouting Module
4.7.3 添加路由出口
4.7.4 添加路由链接
4.7.5 添加仪表盘视图
4.7.6 导航用户详情
4.7.7 支持路由的UserDetailComponent组件

### 4.8 使用HTTP
4.8.1 启用HTTP服务
4.8.2 模拟数据服务器
4.8.3 通过HTTP获取用户数据
4.8.4 修改、添加、删除、搜索用户

### 4.9 “用户管理”应用技术点总结
4.9.1 Angular架构概览
4.9.2 模块
4.9.3 组件
4.9.4 模板、指令和数据绑定
4.9.5 服务与依赖注入
4.9.6 路由


# 第3篇 进阶

## 5. 组件

### [5.1数据展示](https://angular.io/guide/displaying-data)
5.1.1 实例13:数据展示的例子
5.1.2 使用插值表达式显示组件属性
5.1.3 组件关联模板的两种方式
5.1.4 在模板中使用指令

### [5.2 生命周期](https://angular.io/guide/lifecycle-hooks)
5.2.1 生命周期钩子
5.2.2 实例14:生命周期钩子的例子
5.2.3 生命周期钩子的调用顺序
5.2.4 了解 OnInit 钩子
5.2.5 了解 OnDestroy 钩子
5.2.6 了解 OnChanges 钩子
5.2.7 了解 DoCheck 钩子
5.2.8 了解 AfterView 钩子
5.2.9 了解 AfterContent 钩子

### [5.3 组件交互方式](https://angular.io/guide/component-interaction)
5.3.1 实例15通过 @Input 把数据从父组件传到子组件
5.3.2 实例16:通过 setter 监听输入属性值的变化
5.3.3 实例17:通过 ngOnChanges() 方法监听输入属性值的变化
5.3.4 实例18:父组件监听子组件的事件
5.3.5 实例19:父组件与子组件通过本地变量交互
5.3.6 实例20:父组件调用 @viewChild() 方法获取子组件的值
5.3.7 实例21:父组件和子组件通过服务来通信

###  [5.4 样式](https://angular.io/guide/component-styles)
5.4.1 实例22:使用组件样式的例子
5.4.2 样式的作用域
5.4.3 特殊的样式选择器
5.4.4 把样式加载进组件中的几种方式
5.4.5 控制视图的封装模式
5.4.6 了解 Emulated 封装模式

### [5.5 动态加载组件](https://angular.io/guide/dynamic-component-loader)
5.5.1 实例23:动态加载组件的例子
5.5.2 使用指令
5.5.3 加载及解析组件
5.5.4 运行效果

### [5.6 自定义元素](https://angular.io/guide/elements)
5.6.1 使用自定义元素
5.6.2 自定义元素的工作原理
5.6.3 把组件转换成自定义元素
5.6.4 实例24:使用自定义元素的例子

## 6. 模板

### [6.1 模板概述](https://angular.io/guide/template-syntax)
6.1.1 模板的语法
6.1.2 模板中的HTML

### [6.2 模板表达式](https://angular.io/guide/template-syntax#interpolation-and-template-expressions)
6.2.1 模板表达式上下文
6.2.2 编写模板表达式的最佳实践
6.2.3 管道操作符
6.2.4 安全导航操作符和空属性路径
6.2.5 非空断言操作符

### [6.3 模板语句](https://angular.io/guide/template-syntax#template-statements)
6.3.1 模板语句上下文
6.3.2 编写模板语句的最佳实践

### [6.4 数据绑定](https://angular.io/guide/template-syntax#binding-syntax-an-overview)
6.4.1 从数据源到视图
6.4.2 从视图到数据源
6.4.3 双向绑定

### [6.5 属性绑定](https://angular.io/guide/template-syntax#property-binding-property)
6.5.1 单向输入
6.5.2 绑定目标
6.5.3 一次性字符串初始化
6.5.4 选择“插值表达式”还是“属性绑定”

### [6.6 attribute、 class 和 style 绑定](https://angular.io/guide/template-syntax#attribute-class-and-style-bindings)
6.6.1 attribute 绑定
6.6.2 class 绑定
6.6.3 style 绑定

### [6.7 事件绑定](https://angular.io/guide/template-syntax#event-binding-event)
6.7.1 目标事件
6.7.2 $event 和事件处理语句
6.7.3 使用 EventEmitter 类自定义事件

### [6.8 模板引用变量](https://angular.io/guide/template-syntax#template-reference-variables-var)

### [6.9 输入和输出属性](https://angular.io/guide/template-syntax#input-and-output-properties)

## 7. 指令

### [7.1 指令类型](https://angular.io/guide/attribute-directives)

### [7.2 属性型指令](https://angular.io/guide/attribute-directives)
7.2.1 了解 NgClass、NgStyle、NgModel  指令
7.2.2 实例25:创建并使用属性型指令
7.2.3 实例26:响应用户引发的事件
7.2.4 实例27:使用 @Input 数据绑定向指令传递值
7.2.5 实例28:绑定多个属性

### [7.3 结构型指令](https://angular.io/guide/structural-directives)
7.3.1 了解 NgIf 指令
7.3.2 了解 NgSwitch 指令
7.3.3 了解 NgFor 指令
7.3.4 了解 <ng-template> 标签
7.3.5 了解 <ng-container> 标签
7.3.6 实例29:自定义结构型指令

## 8. 管道

### [8.1 使用管道](https://angular.io/guide/pipes)
8.1.1 实例30:使用 Date Pipe 管道
8.1.2 实例31:使用 UpperCasePipe 管道
8.1.3 实例32:使用 LowerCasePipe 管道
8.1.4 实例33:使用 CurrencyPipe 管道
8.1.5 实例34:使用 PercentPipe 管道

### [8.2 对管道进行参数化](https://angular.io/guide/pipes#parameterizing-a-pipe)

### [8.3 链式管道](https://angular.io/guide/pipes#chaining-pipes)

### [8.4 自定义管道](https://angular.io/guide/pipes#custom-pipes)

## 9. 动画

### 9.1 实例35:一个动画的例子
9.1.1 初始化应用
9.1.2 准备工作
9.1.3 创建组件
9.1.4 运行效果

### [9.2 状态与转场](https://angular.io/guide/animations#animation-state-and-styles)
9.2.1 *状态
9.2.2 void状态

### [9.3 进场与离场](https://angular.io/guide/animations#transitions-and-timing)

### [9.4 Animatable 属性与单位](https://angular.io/guide/animations#introduction-to-angular-animations)

### 9.5 自动属性值计算

### [9.6 动画时间线](https://angular.io/guide/animations#transitions-and-timing)
9.6.1 持续时间
9.6.2 延迟
9.6.3 缓动函数
9.6.4 实例36:动画时间线的例子

### [9.7 基于关键帧的多阶段动画](https://angular.io/api/animations/keyframes)
9.7.1 什么是关键帧和偏移量

### [9.8 并行动画组](https://angular.io/api/animations/keyframes)

### [9.9 动画回调](https://angular.io/api/animations/AnimationEvent)

## 10.表单

### [10.1 模板驱动](https://angular.io/guide/forms#template-driven-forms)
10.1.1 实例38:创建表单
10.1.2 实例39:绑定数据
10.1.3 实例40:提交表单

### 10.2 用户输入
10.2.1 实例41:绑定用户输入
10.2.2 实例42:通过 $event 对象取得用户输入
10.2.3 实例43:从一个模板引用变量中获得用户输入
10.2.4 实例44: Enter 键事件
10.2.5 实例45:失去焦点事件

### [10.3 表单验证](https://angular.io/guide/form-validation)
10.3.1 模板驱动验证
10.3.2 响应式表单验证
10.3.3 自定义验证器
10.3.4 自定义样式
10.3.5 跨字段交叉验证

### [10.4 响应式表单](https://angular.io/guide/reactive-forms)
10.4.1 实例46:响应式表单的例子
10.4.2 管理控件的值
10.4.3 实例47:表单控件分组的例子
10.4.4 实例48:嵌套的表单组的例子
10.4.5 使用 patchValue()方法更新部分模型
10.4.6 使用 FormBuilder
10.4.7 使用 FormBuilder 时的表单验证
10.4.8 实例49:使用 FormArray 管理动态控件的例子

### [10.5 动态表单](https://angular.io/guide/dynamic-form)
10.5.1 动态表单的优势
10.5.2 实例50:动态表单的例子


# 第4篇 高阶

## 11. 使用 Observable 与 RxJS实现响应式编程

### [11.1 了解 Observable 机制](https://angular.io/guide/observables) 
11.1.1 了解基本概念
11.1.2 定义观察者
11.1.3 执行订阅
11.1.4 创建 Observable对象
11.1.5 实现多播
11.1.6 处理错误

### [11.2 了解 RxJS 技术](https://angular.io/guide/rx-library)
11.2.1 创建 Observable对象的函数
11.2.2 了解操作符
11.2.3 处理错误

### [11.3 了解 Angular 中的 Observable](https://angular.io/guide/observables-in-angular)
11.3.1 EventEmitter 
11.3.2 HTTP
11.3.3 AsyncPipe 
11.3.4 Router
11.3.5 响应式表单

### [11.4 对比 Observable 对象和 Promise](https://angular.io/guide/comparing-observables#observables-compared-to-promises)
11.4.1 创建与订阅
11.4.2 串联
11.4.3 可取消
11.4.4 错误处理
11.4.5 总结对比结果

### [11.5 对比 Observable 对象和事件 API](https://angular.io/guide/comparing-observables#observables-compared-to-events-api)

### [11.6 对比 Observable 对象和数组](https://angular.io/guide/comparing-observables#observables-compared-to-arrays)

## 12. Angular模块

### [12.1 模块概述](https://angular.io/guide/ngmodules)
12.1.1 什么是模块化
12.1.2 认识基本模块
12.1.3 认识特性模块

### [12.2 引导启动](https://angular.io/guide/bootstrapping)
12.2.1 了解 declarations 数组
12.2.2 了解 imports 数组
12.2.3 了解 providers 数组
12.2.4 了解 bootstrap 数组

### [12.3 常用模块](https://angular.io/guide/frequent-ngmodules)
12.3.1 常用模块概述
12.3.2 BrowserModule 和 CommonModule

### [12.4 特性模块分类](https://angular.io/guide/module-types)
12.4.1 领域特性模块
12.4.2 带路由的特性模块
12.4.3 路由模块
12.4.4 服务特性模块
12.4.5 可视部件特性模块

### [12.5 入口组件](https://angular.io/guide/entry-components)
12.5.1 引导用的入口组件
12.5.2 路由用的入口组件
12.5.3 entryComponents数组
12.5.4 entryComponents数组和编译器

### [12.6 服务提供商](https://angular.io/guide/providers)
12.6.1 创建和提供服务
12.6.2 服务提供商的作用域
12.6.3 providedIn 与 NgModule
12.6.4 使用惰性加载模块限制服务提供商的作用域
12.6.5 使用组件限定服务提供商的作用域
12.6.6 选择模块中的服务还是组件中的服务

### [12.7 单例服务](https://angular.io/guide/singleton-services)
12.7.1 提供单例服务
12.7.2 了解 forRoot()
12.7.3 如何防止重复导入 CoreModule

### [12.8 共享模块](https://angular.io/guide/sharing-ngmodules)
12.8.1 实例51:共享模块的例子
12.8.2 使用来自其他模块的组件和服务

### [12.9 惰性加载的特性模块](https://angular.io/guide/lazy-loading-ngmodules)
12.9.1 实例52:惰性加载特性模块
12.9.2 了解 forRoot()与 forChild()

## 13. 依赖注入

### 13.1 初识依赖注入

### [13.2 实例53:在 Angular中实现依赖注入](https://angular.io/guide/dependency-injection)
13.2.1 初始应用
13.2.2 创建服务
13.2.3 理解注入器
13.2.4 理解服务提供商
13.2.5 注入服务
13.2.6 单例服务
13.2.7 组件的子注入器
13.2.8 测试组件
13.2.9 服务依赖服务
13.2.10 依赖注入令牌
13.2.11 可选依赖

### [13.3 多级依赖注入器](https://angular.io/guide/hierarchical-dependency-injection)
13.3.1 注入器树
13.3.2 注入器冒泡
13.3.3 在不同层级再次提供同一个服务
13.3.4 组件注入器

## 14. 通过HTTP访问网络资源

### [14.1 初识 HttpClient](https://angular.io/guide/http#httpclient)

### 14.2 认识空气质量数据资源

### [14.3 实例54:使用 HttpClient](https://angular.io/guide/http#setup)
14.3.1 导入 HttpClient
14.3.2 编写空气质量组件
14.3.3 编写空气质量服务
14.3.4 注入服务到组件中
14.3.5 返回带类型检查的响应
14.3.6 读取完整的响应体

### [14.4 实例55:错误处理](https://angular.io/guide/http#error-handling)
14.4.1 获取错误详情
14.4.2 重试

### [14.5 实例56:请求非JSON格式的数据](https://angular.io/guide/http#requesting-non-json-data)

### [14.6 实例57:发送数据到服务器](https://angular.io/guide/http#sending-data-to-the-server)
14.6.1 添加请求头
14.6.2 发起 POST 请求
14.6.3 发起 DELETE 请求
14.6.4 发起 PUT 请求

### [14.7 高级用法](https://angular.io/guide/http#advanced-usage)
14.7.1 实例58:配置请求
14.7.2 实例59:请求去抖
14.7.3 实例60:拦截请求和响应
14.7.4 实例61:监听进度

### [14.8 XSRF防护](https://angular.io/guide/http#security-xsrf-protection)
14.8.1 了解 XSRF 防护
14.8.2 实例62:实现XSRF防护

### [14.9 实例63:测试HTTP请求](https://angular.io/guide/http#testing-http-requests)
14.9.1 采用 Mock 方式
14.9.2 设置环境
14.9.3 期望并回复请求
14.9.4 测试对错误的预期

## 15. 路由与导航

### [15.1 路由器的作用](https://angular.io/guide/router)

### [15.2 基础知识](https://angular.io/guide/router#the-basics)
15.2.1 设置<base>标签关联应用目录
15.2.2 从路由库中导入路由器

### [15.3 实例64:配置路由器](https://angular.io/guide/router#configuration)
15.3.1 配置路由器
15.3.2 输出导航生命周期中的事件

### [15.4 实例65:设置路由出口](https://angular.io/guide/router#router-outlet)

### [15.5 理解路由器链接](https://angular.io/guide/router#router-links)
15.5.1 路由器状态
15.5.2 激活的路由

### [15.6 路由事件](https://angular.io/guide/router#router-events)

### [15.7 重定向URL](https://angular.io/guide/router#set-up-redirects)

### 15.8 实例66:一个路由器的例子
15.8.1 创建应用及组件
15.8.2 修改组件的模板
15.8.3 导入并设置路由器
15.8.4 添加路由出口
15.8.5 美化界面
15.8.6 定义通配符路由

## 16. 测试

### [16.1 测试准备](https://angular.io/guide/testing)

### [16.2 认识测试工具](https://angular.io/guide/testing#setup)
16.2.1 认识 Jasmine和 Karma
16.2.2 配置 Jasmine和 Karma
16.2.3 启用代码覆盖率报告
16.2.4 了解测试工具API

### [16.3 理解组件测试](https://angular.io/guide/testing#component-test-basics)
16.3.1 实例67:单独测试组件类
16.3.2 测试组件DOM

### [16.4 实例68:测试服务](https://angular.io/guide/testing#service-tests)
16.4.1 测试普通服务
16.4.2 测试带有依赖的服务
16.4.3 测试HTTP服务

### [16.5 实例69:测试属性型指令](https://angular.io/guide/testing#attribute-directive-testing)

### [16.6 实例70:测试管道](https://angular.io/guide/testing#pipe-testing)

### [16.7 调试测试程序](https://angular.io/guide/testing#test-debugging)

## 17. 实现国际化

### [17.1 国际化概述](https://angular.io/guide/http#testing-http-requests)

### [17.2 实例71:通过i18n工具来实现国际化](https://angular.io/guide/i18n#angular-and-i18n)
17.2.1 使用i18n属性
17.2.2 在i18n属性中添加描述
17.2.3 在i18n属性中添加意图
17.2.4 创建翻译源文件
17.2.5 了解翻译源文件
17.2.6 创建翻译文件
17.2.7 增加应用配置
17.2.8 运行应用

### 17.3 实例72:通过 ngx-translate 插件实现国际化
17.3.1 添加 ngx-translate 库
17.3.2 导入并配置 ngx-translate 模块
17.3.3 注入 TranslateService 服务
17.3.4 编写翻译文件
17.3.5 使用 ngx-translate
17.3.6 运行应用

## 18. 编译与部署 Angular 应用程序

### [18.1 编译 Angular应用程序](https://angular.io/guide/aot-compiler)
18.1.1 编译概述
18.1.2 编译分类
18.1.3 为什么需要AOT编译

### [18.2 了解 Angular模板编译器选项](https://angular.io/guide/angular-compiler-options)

### [18.3 理解 Angular元数据与AOT](https://angular.io/guide/aot-metadata-errors)
18.3.1 理解元数据的限制
18.3.2 理解AOT的工作原理

### [18.4 部署 Angular应用程序](https://angular.io/guide/deployment)
18.4.1 最简化的部署方式
18.4.2 为生产环境准备的部署方式

## 19. 页面静态化

### [19.1 Universal 概述](https://angular.io/guide/universal)
19.1.1 了解 Universal
19.1.2 使用 Universal的好处

### 19.2 初始化 Universal示例

### 19.3 实例73:使用 Universal
19.3.1 安装工具
19.3.2 修改根模块 AppModule
19.3.3 创建 AppModule模块
19.3.4 创建main文件
19.3.5 创建 App ServerModule配置文件
19.3.6 创建新的构建目标并打包
19.3.7 设置服务器环境
19.3.8 打包并运行应用

## 20. 启用缓存

### [20.1 了解 Service Worker](https://angular.io/guide/service-worker-intro)

### [20.2 实例74:使用 Service Worker](https://angular.io/guide/service-worker-getting-started)
20.2.1 添加 service-worker 包
20.2.2 用 http-server 启动服务器
20.2.3 模拟网络故障
20.2.4 查看缓存内容
20.2.5 修改应用
20.2.6 在浏览器中更新应用

### [20.3 了解 Service Worker 的通信机制](https://angular.io/guide/service-worker-communications)
20.3.1 有可用更新和已激活更新
20.3.2 检查更新
20.3.3 強制激活更新
20.3.3 强制激活更新

### [20.4 配置 Service Worker](https://angular.io/guide/service-worker-config)



# 第5篇 商业实战

## 21. 新闻头条客户端总体设计

### 21.1 应用概述

### 21.2 需求分析
21.2.1 首页需求分析
21.2.2 新闻详情页面需求分析

### 21.3 架构设计
21.3.1 获取访问API的密钥
21.3.2 了解新闻API

### 21.4 实例75:初始化新闻头条客户端应用
21.4.1 修改 app.component.htm
21.4.2 修改app.component.ts
21.4.3 启动应用

## 22. 实现新闻头条客户端首页

### 22.1 首页需求分析

### 22.2 首页架构设计

### 22.3 实例76:实现新闻头条客户端首页
22.3.1 添加 AngularMaterial
22.3.2 配置动画
22.3.3 导入组件模块
22.3.4 包含一个主题
22.3.5 创建组件
22.3.6 实现界面原型
22.3.7 查看完整的首页原型效果

## 23. 实现新闻头条客户端导航栏

### 23.1 导航栏概述

### 23.2 导航栏需求分析

### 23.3 导航栏架构设计

### 23.4 实例77:实现新闻头条客户端新间分类
23.4.1 新建新闻分类服务
23.4.2 解析新闻分类数据
23.4.3 展示新闻分类

### 23.5 实例78:实现新闻头条客户端新闻列表
23.5.1 新建新闻列表服务
23.5.2 解析新闻列表数据
23.5.3 展示新闻列表

### 23.6 实例79:实现新闻分类与新闻列表组件通信
23.6.1 监听导航栏单击事件
23.6.2 自定义导航切换事件
23.6.3 监听导航切换事件
23.6.4 运行应用

## 24. 实现新闻头条客户端新闻详情页面

### 24.1 新闻详情页面概述

### 24.2 新闻详情页面需求分析

### 24.3 新闻详情页面架构设计

### 24.4 实例80:实现新闻头条客户端新闻详情页面
24.4.1 新建新闻详情组件及服务
24.4.2 获取新闻详情数据
24.4.3 展示新闻详情
24.4.4 创建首页组件
24.4.5 创建路由器
24.4.6 修改新闻列表组件
24.4.7 接收路由参数
24.4.8 增加“返回”按钮
24.4.9 运行应用



[源码地址](https://github.com/waylau/angular-enterprise-application-development-samples)