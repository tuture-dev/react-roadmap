# React 前端工程师学习路线

<a name="nkCtA"></a>

这里有从你敲下第一行 HTML 代码开始，到了解、学习、掌握最前沿的 React Web 前端开发所必须技能的学习路线图。

路线图是根据社区贡献者的共同改进所得，力求贴近时代前沿技术，以如下方式组织：

- 技术名称
- 技术学习涵盖的知识点
- 技术对应的学习教程以及对应包含上面提到的1到多个知识点
- 撰写对应教程所参考的资源
- 参与贡献的用户

路线自顶向下涉及到的内容难度逐渐增加，但路线对应知识点和教程的设计却充分考虑到了不同背景的学习者需求：

- 作为初学者，你可以跟着路线一步一步学习，直到完成所有内容。
- 作为有一定基础的学习者，你可以挑选其中你感兴趣的技术进行学习，因为路线往后的教程内容所涉及的代码不会依赖路线更前的教程，所以你无需担心可能存在的依赖关系。
- 甚至是单纯为了解决某个 React 方向上的难题的学习者，你也可以从路线中获取到对应的帮助。

## 入门

<a name="RGc20"></a>

### HTML 基础

<a name="qnpZa"></a>

#### 知识点

1. Web 背景知识及超文本标记语言的介绍
2. 常用标签及其对应属性的介绍： `<head>`， `<title>`， `<bodu>` ， `<p>` ， `<div>` ， `<span>` ， `<img>` ， `<form>` ， `<input>` ， `<button>` 等
3. Emmet 了解和使用

<a name="o3NnF"></a>

#### 教程规划

《HTML 快速入门教程》-> 知识点 1,2,3

<a name="4frNj"></a>

### CSS 基础

<a name="EwMd6"></a>

#### 知识点

1. CSS 规则集介绍：选择器、声明、属性、属性值
2. 盒子模型

<a name="YsdGq"></a>

#### 教程规划

《CSS 快速入门教程》-> 知识点 1,2

<a name="2Br9z"></a>

### JavaScript 基础

<a name="50xBi"></a>

#### 知识点

1. 变量、注释、运算符、条件语句、循环，函数、事件的基础概念及其相关操作介绍
2. ES6 相关的 `const` , `let` , `arrow function` , `classes` , `{ ... }` , 函数默认值的概念

<a name="zWVIX"></a>

#### 教程规划

《JavaScript 快速入门教程》-> 知识点 1,2

<a name="7QmTU"></a>

### Node.js 环境搭建

<a name="4osDp"></a>

#### 知识点

1. 不同平台（Linux、macOS、Windows）的安装
1. 编辑器环境搭建，主要是 VSCode，包括如何与 ESLint、Prettier 等插件集成
1. nvm 工具的使用
1. 配置 npm 源，加速依赖安装

<a name="RPNlU"></a>

#### 教程规划

《Node.js 环境搭建指南》-> 知识点 1,2,3,4

<a name="yQsKU"></a>

#### 参考内容

- [《一起学 Node.js》1.1 节](https://github.com/nswbmw/N-blog/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md)
- [《Node.js 包教不包会》Lesson 0](https://github.com/alsotang/node-lessons/tree/master/lesson0)
- [菜鸟教程 Node.js 安装配置](https://www.runoob.com/nodejs/nodejs-install-setup.html)
- [VSCode JavaScript 语言开发官方文档](https://code.visualstudio.com/docs/languages/javascript)

<a name="46tO2"></a>

### React

<a name="fsBPI"></a>

#### 知识点

1. JSX，ReactDOM.render，Component 和 Props，State，处理事件，条件渲染，循环和 key，表单
1. React 中使用样式和静态资源
1. React LifeCycle Hooks，可控组件，Lifting State Up，高阶组件，Refs，静态属性检查，Context
1. React Hooks
1. 错误处理，性能优化，Profiler

<a name="oVlL3"></a>

#### 教程规划

《React 快速入门教程（一）》-> 知识点 1<br />《React 快速入门教程（二）》-> 知识点 2<br />《React 快速入门教程（三）》-> 知识点 3<br />《React 快速入门教程（四）》-> 知识点 4<br />《React 快速入门教程（五）》-> 知识点 5

<a name="2LBaL"></a>

### React Router

<a name="W6xFg"></a>

#### 知识点

1. <br />

<a name="EWgtj"></a>

#### 教程规划

《React Router 快速入门教程》

<a name="o3NZ6"></a>

## 进阶

<a name="Kfuc3"></a>

### HTTP

<a name="35hVw"></a>

#### 知识点

1. <br />

<a name="dJqGx"></a>

#### 教程规划

《HTTP 快速入门教程》

<a name="vaLZr"></a>

### Redux 

<a name="kE618"></a>

#### 知识点

1. Redux 三大概念：Store，Action，Reducers
1. 状态组合：combineRedcuers
1. 状态与展示分离：Presentational Component & Container Component
1. 异步 Actions 和 异步 Flow，中间件，Enhancer，与 React Router 搭配使用
1. DVA 的使用

<a name="4RrUO"></a>

#### 教程规划

《Redux 快速入门教程》-> 知识点 1,2,3<br />《Redux 进阶 教程》-> 知识点 4<br />《Redux 框架篇 --- DVA 的使用》-> 知识点 5

<a name="0oE3m"></a>

### 小程序开发

<a name="3vE7J"></a>

#### 知识点

1. Web 到小程序开发的一些配置的转变和约定，小程序路由相对于 Web 路由的区别，使用 Taro 在小程序中开发需要遵守的约定，如何使用样式和静态资源
1. 开发工具的调试
1. 应用的发布

<a name="dVYad"></a>

#### 教程规划

《使用 React 框架 Taro 开发小程序之从入门到上线》-> 知识点 1,2,3

<a name="OvFqv"></a>

### 移动应用开发

<a name="6x4wZ"></a>

#### 知识点

1. react-native 中定义一套组件库对应到 HTML
1. CSS-layout
1. 开发工具的调试
1. 应用的打包与发布上线

<a name="QRB3E"></a>

#### 教程规划

《使用 React Native 开发移动 App 之从入门到上线》-> 知识点 1,2,3,4

<a name="u0sU3"></a>

### 桌面端应用开发

<a name="J0FRv"></a>

#### 知识点

<a name="v7VW9"></a>

#### 教程规划

<a name="NHdOi"></a>

### IoT 端应用开发

<a name="Al0Ua"></a>

#### 知识点

<a name="1yGvH"></a>

#### 教程规划

<a name="w0Fkx"></a>

### VR、AR 应用开发

<a name="fADKb"></a>

#### 知识点

<a name="R1eIv"></a>

#### 教程规划

<a name="h5jBS"></a>

## 工具

<a name="xlwqK"></a>

### ESLint

<a name="d489b"></a>

### Prettier

<a name="0R1HX"></a>

### Babel

<a name="HneLB"></a>

### Webpack

<a name="ouD0G"></a>

### StyleLint

<a name="scM0q"></a>

## 前沿概念

<a name="7IGN0"></a>

### 组件库

<a name="aI62x"></a>

### TypeScript

<a name="Elzqz"></a>

### 服务端渲染

<a name="WOxb9"></a>

### 微前端

<a name="5r55b"></a>

### 测试

<a name="4u7BZ"></a>

### 部署

<a name="xDoFa"></a>

## 样式

<a name="YEBpg"></a>

### 响应式

<a name="OoPi7"></a>

### CSS Modules

<a name="s1rJX"></a>

### CSS in JS
