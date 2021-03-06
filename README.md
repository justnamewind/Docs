# Docs

**该项目是什么？**

信息技术知识结构

**该项目有什么用？**

用于辅助记忆

**需要记录什么？**

官方文档已经很好了，为什么要自己写？结构树的核心是目录，只要整理好目录就没必要自己在写一遍文档，只记录实践过的，学习的不需要记录

**怎么记录？**

每个文件下都有一个readme.md文件，用于记录

## 结构规范

### 一级目录

**什么情况下需要创建一级目录？**

作为应用，需要系统安装的。如：sdk，git，编辑器。

### 二级目录

## readme.md规范

- 官方链接
- install链接

## 缩略图

- [xcode](https://github.com/dreamius/Docs/tree/master/xcode)
- [cocoapods](https://github.com/dreamius/Docs/tree/master/cocoapods)
- [android studio](https://github.com/dreamius/Docs/tree/master/android%20studio)
- [flutter](https://github.com/dreamius/Docs/tree/master/flutter)
- [vscode](https://github.com/dreamius/Docs/tree/master/vscode)

### API目录规范

- [property/method(params)](http://)
  - params
    - params.property

- lang
  - statements
  - global_objects
  - sdk
    - nodejs
    - browser
      - html
        - css
    - flutter
    - dart sdk
  - package
    - cli
    - lib
  - typescript


## 核心文档

- 判断是否需要学会
  - 需要熟读文档

  - 判断21天内是否能够学会
    - 集中精力去熟读
    - 搭好结构，拆成任务，长期去读

## 文档

- 判断是否可以成为一个package
  - 是
    - 判断是否可以import

## nodejs

nodejs需要学会，并且21天内无法学会

- nodejs*
  - package
    - cli
      - npm
    - lib

- dart
  - package


## 54321go

action manager




electron
capacitor
flutter

vue
angular
react
svelte


## 文档规范

- 操作系统
  - 环境变量
    - path
- javascript
  - package
  - sdk
  - 内置
    - module
      - commonjs*
      - requirejs*
    - object
    - array
  - web api
    - documnet
    - worker*
    - blob
  - typescript*
  - framwork
    - svelte*
    - worker-dom*
    - capacitor
    - cordova
    - ionic
    - angular

- powershell
- git
- vscode
- android
## language

* markdown

* html

* css

  * sass

* xml

* json

* yaml

* javascrpit

  * typescript

* dart

* shell

  * powershell

## framework

* angular.js

* ionic

* node.js

* flutter

## tool

* webpack

* git

* vscode
 
* android studio



## 计算机组成原理

## 数据结构

## 操作系统

### 进程

#### 线程

* worker

## 计算机网络

### 协议

* blob







## 面向对象

看成一个对象，有属性和方法。将多个耦合的方法和属性有封装成一个class，没有class可以在函数中通过return返回属性和方法，所以需要return多个的时候，可以用class

- 属性
  - 普通属性
  - set属性
  - get属性
- 方法
  - 构造函数
  - 普通函数

### 命令式

由上至下一行一行代码执行

### 函数式

看成一个方法。将多行代码封装成一个函数

### 继承

#### 多重继承

## 异步

异步是提前使用未来的值，在await时该值暂时不可用，等待完成后才可以用

### 同步/异步和阻塞/非阻塞

- callback
  
  将函数fn1作为参数传给另一个函数fn2，fn1在fn2中被调用，回调函数返回的参数只能用另一个回调函数来使用
- promise

### 事件循环、栈（同步）、队列（回调）

### 全栈

全栈不是前后端的技术都要强，也不是说前后端都要做，而是要有全栈思维，提高认知的宽度，提高理解能力。不会前端不懂后端在讲什么，后端不懂前端在讲什么

## 声明式UI

angular、react、vue实际上是构建声明式UI的js框架，声明式UI的核心是数据(state)在视图层(view)的变化，后来的swiftUI和flutter都属于这种类型的框架







### 文档结构

属性和方法用\-表示
- method(option)
  - option.property
- property


## electron
  - quick start
    - env
    - create
    - install
    - run




## 看源码技巧

不可能从头到尾看，太花时间

从点到面，抓住关键函数，能理解函数内部实现。然后再查看谁调用了这个函数，参数从哪里传过来的
