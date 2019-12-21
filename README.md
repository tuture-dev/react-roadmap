<div align="center" id="top">
	<img style="display: inline;" width="100%" src="./assets/images/Logo.svg" />
  <h1>
    React 前端工程师学习路径
  </h1>
  <p>
    React 是一个用于构建用户界面的 JavaScript 库，具有优秀的性能，并且它的声明式、组件化特性让编写代码变得简单。这条学习路径将带你熟悉前端开发的基础知识，然后深入学习 React、React Router 及 Redux 等关键组件，熟悉 ESLint、Webpack 等常用工具，最后还会涉及小程序开发、跨平台移动端开发、服务器端渲染等热门话题，最终成为一名优秀的 React 前端工程师。
  </p>
</div>

## 目录 <!-- omit in toc -->

- [入门](#%e5%85%a5%e9%97%a8)
  - [Web](#web)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90)
  - [HTML](#html)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-1)
  - [CSS](#css)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-1)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-2)
  - [JavaScript](#javascript)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-2)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-3)
  - [HTTP 协议](#http-%e5%8d%8f%e8%ae%ae)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-3)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-4)
  - [Node.js](#nodejs)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-4)
    - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-5)
  - [React](#react)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-5)
    - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-1)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-6)
  - [React Router](#react-router)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-6)
    - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-2)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-7)
- [进阶](#%e8%bf%9b%e9%98%b6)
  - [Redux](#redux)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-7)
    - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-3)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-8)
  - [小程序开发](#%e5%b0%8f%e7%a8%8b%e5%ba%8f%e5%bc%80%e5%8f%91)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-8)
    - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-4)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-9)
  - [移动应用开发](#%e7%a7%bb%e5%8a%a8%e5%ba%94%e7%94%a8%e5%bc%80%e5%8f%91)
  - [桌面端应用开发](#%e6%a1%8c%e9%9d%a2%e7%ab%af%e5%ba%94%e7%94%a8%e5%bc%80%e5%8f%91)
  - [VR 应用开发](#vr-%e5%ba%94%e7%94%a8%e5%bc%80%e5%8f%91)
- [工具](#%e5%b7%a5%e5%85%b7)
  - [ESLint](#eslint)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-9)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-10)
  - [Prettier](#prettier)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-10)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-11)
  - [Babel](#babel)
    - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-11)
    - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-12)
  - [Webpack](#webpack)
  - [StyleLint](#stylelint)
- [前沿概念](#%e5%89%8d%e6%b2%bf%e6%a6%82%e5%bf%b5)
  - [组件库](#%e7%bb%84%e4%bb%b6%e5%ba%93)
  - [TypeScript](#typescript)
  - [服务端渲染](#%e6%9c%8d%e5%8a%a1%e7%ab%af%e6%b8%b2%e6%9f%93)
  - [微前端](#%e5%be%ae%e5%89%8d%e7%ab%af)
  - [测试](#%e6%b5%8b%e8%af%95)
  - [部署](#%e9%83%a8%e7%bd%b2)

## 入门

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/web.svg">

### Web
</div>

> 我们平时使用手机或者电脑浏览的网页，如你经常使用的百度主页，它是一个网页，你通过百度的输入框输入内容，然后点击搜索，出现的搜索内容又是另外一个网页。

#### 参考资源

- [MDN 上的 Web 入门部分 -- Web 的概述](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [MDN 上的 Web 入门部分 -- 您的网站会是什么样的？](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- [MDN 上的 Web 入门部分 -- 万维网是如何运作的？](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [MDN 上的 Web 入门部分 -- 安装基本软件](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/Installing_basic_software)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/html-5.svg">

### HTML
</div>

> HTML（超文本标记语言——HyperText Markup Language）是构成 Web 世界的一砖一瓦。它定义了网页内容的含义和结构。除 HTML 以外的其它技术则通常用来描述一个网页的表现与展示效果（如 CSS），或功能与行为（如 JavaScript）。


#### 知识点 

1. 学习 HTML 的基础知识
2. HTML 语法
3. 将页面划分为多个部分并正确构建 DOM

#### 参考资源

- [MDN 上的 HTML 部分的 HTML 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/css-3.svg" />

### CSS
</div>

> 层叠样式表 (Cascading Style Sheets，缩写为 CSS），是一种 样式表 语言，用来描述 HTML 或 XML（包括如 SVG、MathML、XHTML 之类的 XML 分支语言）文档的呈现。CSS 描述了在屏幕、纸质、音频等其它媒体上的元素应该如何被渲染的问题。

#### 知识点

1. 学习 CSS 的基础知识
2. Grid 布局和 Flexbox 布局
3. 响应式 Web 设计和媒体查询

#### 参考资源

- [MDN 上 CSS 部分的 CSS 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/CSS_basics)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/javascript.svg">

### JavaScript
</div>

> JavaScript ( JS ) 是一种具有函数优先的轻量级，解释型或即时编译型的编程语言。虽然它是作为开发Web 页面的脚本语言而出名的，但是它也被用到了很多非浏览器环境中，例如 Node.js、 Apache CouchDB 和 Adobe Acrobat。JavaScript 是一种基于原型编程、多范式的动态脚本语言，并且支持面向对象、命令式和声明式（如函数式编程）风格。了解更多 JavaScript。

#### 知识点

1. 语法和基本的操作
2. DOM 操作
3. 变量提升，事件冒泡，原型
4. AJAX（XHR）
5. ECMAScript 6+，学习新的特性

#### 参考资源

- [MDN 上 JavaScript 部分的 JavaScript 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/http.svg">

### HTTP 协议
</div>

> HTTP是一种能够获取如 HTML 这样的网络资源的 protocol(通讯协议)。它是在 Web 上进行数据交换的基础，是一种 client-server 协议，也就是说，请求通常是由像浏览器这样的接受方发起的。一个完整的Web文档通常是由不同的子文档拼接而成的，像是文本、布局描述、图片、视频、脚本等等。

#### 知识点

1. HTTP 的基本性质
2. HTTP 能控制什么？
3. HTTP 流
4. HTTP 报文
5. 基于 HTTP 的 APIs

#### 参考资源

- [MDN 关于 HTTP 的概述](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Overview)
- [阮一峰的 HTTP 协议入门](http://www.ruanyifeng.com/blog/2016/08/http.html)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/nodejs.svg">

### Node.js
</div>

> 简单的说 Node.js 就是运行在服务端的 JavaScript。Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台。Node.js是一个事件驱动I/O服务端JavaScript环境，基于Google的V8引擎，V8引擎执行Javascript的速度非常快，性能非常好。

#### 知识点

1. 不同平台（Linux、macOS、Windows）的安装
2. 编辑器环境搭建，主要是 VSCode，包括如何与 ESLint、Prettier 等插件集成
3. nvm 工具的使用
4. 配置 npm 源，加速依赖安装

#### 实战教程

- ✍️《Node.js 开发环境搭建》 🗝知识点 1, 2, 3, 4
- ✅[《Node.js 快速入门教程》](https://tuture.co/2019/12/03/892fa12/) 🗝知识点 3, 4, 5

#### 参考资源

- [一起学 Node.js - 1.1 节](https://github.com/nswbmw/N-blog/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md)
- [Node.js 包教不包会 - Lesson 0](https://github.com/alsotang/node-lessons/tree/master/lesson0)
- [菜鸟教程 - Node.js 安装配置](https://www.runoob.com/nodejs/nodejs-install-setup.html)
- [VSCode JavaScript 语言开发官方文档](https://code.visualstudio.com/docs/languages/javascript)
- [MDN - Express 教程之架设 Node(Express) 开发环境](https://developer.mozilla.org/zh-CN/docs/Learn/Server-side/Express_Nodejs/development_environment)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/react-1.svg">

### React
</div>

> React 是一个用于构建用户界面的 JAVASCRIPT 库。React 主要用于构建UI，很多人认为 React 是 MVC 中的 V（视图）。React 起源于 Facebook 的内部项目，用来架设 Instagram 的网站，并于 2013 年 5 月开源。React 拥有较高的性能，代码逻辑非常简单，越来越多的人已开始关注和使用它。

#### 知识点

1. JSX，ReactDOM.render，Component 和 Props，State，处理事件，条件渲染，循环和 key，表单
2. 深入理解 JSX，React 中使用样式和静态资源，React LifeCycle Hooks，可控组件，Lifting State Up，高阶组件，Refs，静态属性检查
3. 请求 API，Context，React Hooks
4. 高级概念
   1. 错误处理
   2. Profiler
   3. 性能优化
   4. Portals
   5. Fragments
   6. 可访问性
   7. 代码拆分
   8. Web 组件
   9. 可访问性
   10. 严格模式
   11. 测试

#### 实战教程

- ✅[《React 快速入门教程》](https://tuture.co/2019/11/18/07acf61/) 🗝知识点 1
- ✅[《用 React 做一个井字棋小游戏（一）》](https://tuture.co/2019/11/13/175b717/) 🗝 知识点 1，以及 2 中的 React 中使用样式和静态资源, Lifting State Up
- ✅[《用 React 做一个井字棋小游戏（二）》](https://tuture.co/2019/11/13/3697248/) 🗝 知识点 1，以及 2 中的可控组件，Lifting State Up
- ✍️《React 进阶教程（一）》 🗝知识点 2
- ✍️《React 进阶教程（二）》 🗝知识点 4.1, 4.2, 4.5, 4.5
- ✍️《React 进阶教程（三）》 🗝知识点 4.6, 4.8, 4.9, 4.10
- ✍️《React 性能优化教程》 🗝知识点 4.3, 4.7
- ✍️《React 测试教程》 🗝知识点 4.11
- ✍️《React Hooks 教程》 🗝知识点 3

#### 参考资源

- [React 官方中文文档](https://zh-hans.reactjs.org/)
- [阮一峰的 React 技术栈教程](http://www.ruanyifeng.com/blog/2016/09/react-technology-stack.html)
- [菜鸟教程的 React 学习部分](https://www.runoob.com/react/react-tutorial.html)
- [React.js 小书](http://huziketang.mangojuice.top/books/react/)
- [React入门教程 – 概述和实际演练](https://www.html.cn/archives/9710)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/react-router.svg">

### React Router
</div>

> 组件是 React 的核心功能，其拥有非常强大的声明式编程模型。React Router 是导航组件的集合，可与你的应用程序进行声明式的组合。无论你是想为你的 Web 应用程序添加书签，还是在 React Native 中进行组件化导航，React Router 都可以在 React 的任何位置渲染使用。

#### 知识点

1. 路由基础（静态路由和动态路由说明），URL 参数，嵌套路由，重定向，自定义链接，404，路由的查询参数，路由配置，静态路由上下文等
2. 服务端渲染
3. 测试
4. 与 Redux 整合
5. 高阶内容或例子
   1. 路由过渡动画
   2. 递归路由
   3. 侧边栏路由
   4. 滚动恢复
   5. 代码拆分

#### 实战教程

- ✍️《React Router 快速入门教程》 🗝知识点 1
- ✍️《React Router 服务端渲染教程》 🗝知识点 2
- ✍️《React Router 测试教程》 🗝知识点 3
- ✍️《React Router 与 Redux 整合》 🗝知识点 4
- ✍️《React Router 高阶内容或例子（一）》 🗝知识点 5.1，5.2，5.3
- ✍️《React Router 高阶内容或例子（二）》 🗝知识点 5.4，5.5

#### 参考资源

- [React Router 官方文档](https://reacttraining.com/react-router/) 🇺🇸
- [React Router 官方文档](https://react-router.docschina.org/) 🇨🇳
- [阮一峰的 React Router 教程](https://react-router.docschina.org/) 🇨🇳
- [知乎上的 React Router 入门教程](https://zhuanlan.zhihu.com/p/78176856) 🇨🇳
- [关于 React Router v4 的一切](https://juejin.im/post/5995a2506fb9a0249975a1a4) 🇨🇳
- [简明 React Router v4 教程](https://juejin.im/post/5a7e9ee7f265da4e7832949c) 🇨🇳

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

## 进阶

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/redux.svg">

### Redux
</div>

> Redux 是 JavaScript 状态容器，提供可预测化的状态管理。可以让你构建一致化的应用，运行于不同的环境（客户端、服务器、原生应用），并且易于测试。不仅于此，它还提供 超爽的开发体验，比如有一个时间旅行调试器可以编辑后实时预览。Redux 除了和 React 一起用外，还支持其它界面库。 它体小精悍（只有2kB，包括依赖）。

#### 知识点

1. Redux 的介绍及与 React 的关系
2. 三大核心概念：Store，Reducers，Action
3. combineRedcuers，connect
4. 容器组件，展示组件
5. 异步 Action，异步 Flow
6. 搭配 React Router
7. 高阶概念：
   1. 中间件
   2. Enhancers
   3. 服务端渲染
   4. 测试

#### 实战教程

- ✅[《Redux 快速入门教程（一）》](https://tuture.co/2019/11/28/466324a/) 🗝知识点 1
- ✅[《Redux 快速入门教程（二）》](https://tuture.co/2019/11/28/1fe175a/) 🗝知识点 2
- ✅[《Redux 快速入门教程（三）》](https://tuture.co/2019/11/28/e78884e/) 🗝知识点 3
- ✅[《Redux 快速入门教程（四）》](https://tuture.co/2019/11/28/7dda333/) 🗝知识点 4
- ✍️《Redux 进阶教程（一）》 🗝知识点 5
- ✍️《Redux 进阶教程（二）》 🗝知识点 6
- ✍️《Redux 进阶教程（三）》 🗝知识点 7.1, 7.2
- ✍️《Redux 服务端渲染教程》 🗝知识点 7.3
- ✍️《Redux 测试教程》 🗝知识点 7.4

#### 参考资源

- [Redux 官方文档](https://redux.js.org/)
- [Redux 中文文档](https://www.redux.org.cn/)
- [Redux Tutorial 中文翻译](https://github.com/react-guide/redux-tutorial-cn)
- [阮一峰的 Redux 入门教程（一）：基本用法](http://www.ruanyifeng.com/blog/2016/09/redux_tutorial_part_one_basic_usages.html)
- [阮一峰的 Redux 入门教程（二）：中间件与异步操作](http://www.ruanyifeng.com/blog/2016/09/redux_tutorial_part_two_async_operations.html)
- [阮一峰的 Redux 入门教程（三）：React Redux 的用法](http://www.ruanyifeng.com/blog/2016/09/redux_tutorial_part_three_react-redux.html)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/miniprogram.svg">

### 小程序开发
</div>

> 小程序，英文名Mini Program，是一种不需要下载安装即可使用的应用，它实现了应用“触手可及”的梦想，用户扫一扫或搜一下即可打开应用。
> 这里专门介绍使用 Taro 小程序多端统一开发框架来进行小程序开发。
> Taro 是一套遵循 React 语法规范的 多端开发 解决方案。
> 现如今市面上端的形态多种多样，Web、React-Native、微信小程序等各种端大行其道，当业务要求同时在不同的端都要求有所表现的时候，针对不同的端去编写多套代码的成本显然非常高，这时候只编写一套代码就能够适配到多端的能力就显得极为需要。
> 使用 Taro，我们可以只书写一套代码，再通过 Taro 的编译工具，将源代码分别编译出可以在不同端（微信/百度/支付宝/字节跳动/QQ小程序、快应用、H5、React-Native 等）运行的代码。

#### 知识点

1. Taro 简介，多端编译原理
2. 与 React 的相同之处，以及对应的限制
3. 小程序平台相关的配置
4. 小程序路由系统
5. 样式
   1. CSS Modules 的使用
6. 静态资源引用
7. 小程序相关概念：
   1. 如何调试？
   2. 小程序特色 API
   3. 小程序云开发
   4. 小程序编辑器介绍
8. 进阶概念：
   1. Redux 使用
   2.  测试
   3.  性能优化
   4.  使用 React Hooks
   5.  如何编译到多端？
   6.  部署上线
9.  使用 taro-ui 组件库来加速开发
10. 使用数据分析工具进行前端埋点

#### 实战教程

- ✍️《使用 Taro 实现一个点餐小程序（一）》 🗝知识点 1,2,3
- ✍️《使用 Taro 实现一个点餐小程序（二）》 🗝知识点 4, 5, 6, 9
- ✍️《使用 Taro 实现一个点餐小程序（三）》 🗝知识点 7.1, 7.2, 7.4
- ✍️《使用 Taro 实现一个点餐小程序（四）》 🗝知识点 7.3
- ✍️《使用 Taro 实现一个点餐小程序（五）》 🗝知识点 8.1
- ✍️《使用 Taro 实现一个点餐小程序（六）》 🗝知识点 8.5, 8.6
- ✍️《使用 Taro 实现一个点餐小程序（七）》 🗝知识点 8.2
- ✍️《使用 Taro 实现一个点餐小程序（八）》 🗝知识点 8.3
- ✍️《使用 Taro 实现一个点餐小程序（九）》 🗝知识点 8.4
- ✍️《使用 Taro 实现一个点餐小程序（十）》 🗝知识点：10

#### 参考资源

- [Taro 官网](https://taro.jd.com/)
- [Taro 官方文档](http://taro-docs.jd.com/taro/docs/README.html)
- [Taro 官网](https://taro.jd.com/)
- [Taro UI 官网](https://taro-ui.jd.com/#/)
- [多端统一开发框架 - Taro](https://aotu.io/notes/2018/06/07/Taro/)
- [小程序框架全面评测](https://aotu.io/notes/2019/03/12/mini-program-framework-full-review/)
- [Taro 1.3 震撼升级：全面支持 JSX 语法和 HOOKS](https://aotu.io/notes/2019/06/13/taro-1-3/)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/apple.svg">
<img style="display: inline;" width="100" height="100" src="./assets/images/android-icon.svg">

### 移动应用开发
</div>

> 移动应用程序开发是为移动设备开发移动应用程序的行为或过程，例如个人数字助理，企业数字助理或移动电话。这些应用程序可以在制造平台期间预先安装在手机上，或者使用服务器端或客户端处理作为Web应用程序提供，以在Web浏览器中提供“类似应用程序”的体验。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/electron.svg">

### 桌面端应用开发
</div>

> Electron是GitHub开发的一个开源框架。它允许使用Node.js和Chromium完成桌面GUI应用程序的开发。Electron现已被多个开源Web应用程序用于前端与后端的开发，著名项目包括GitHub的Atom和微软的Visual Studio Code。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/vr.svg">

### VR 应用开发
</div>

> 虚拟现实（英语：virtual reality，缩写VR），简称虚拟技术，也称虚拟环境，是利用电脑模拟产生一个三维空间的虚拟世界，提供用户关于视觉等感官的模拟，让用户感觉仿佛身历其境，可以即时、没有限制地观察三维空间内的事物。用户进行位置移动时，电脑可以立即进行复杂的运算，将精确的三维世界影像传回产生临场感。该技术集成了电脑图形、电脑仿真、人工智能、感应、显示及网络并行处理等技术的最新发展成果，是一种由电脑技术辅助生成的高技术模拟系统。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

## 工具

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/eslint.svg">

### ESLint
</div>

> ESLint（有时发音为Easy Lint）是一种静态代码分析工具，用于识别JavaScript代码中发现的有问题的模式。 它由Nicholas C. Zakas在2013年创建。ESLint中的规则是可配置的，并且可以定义和加载自定义规则。 ESLint涵盖了代码质量和编码样式问题。 ESLint支持ECMAScript的当前标准，以及草案中用于将来标准的实验语法。 使用插件或编译器时，也可以使用JSX或TypeScript进行代码处理。

#### 知识点

1. ESLint 的来源、应用、如何运作、寻找合适的规则
2. ESLint 高级配置
3. 命令行选项
4. 将 ESLint 集成到其它工具中，比如编辑器，构建工具等。
5. 创建自定义规则

#### 参考资源

- [ESLint 中文官网](http://eslint.cn/)
- [ESLint 超简单入门教程](https://www.jianshu.com/p/ad1e46faaea2)
- [深入浅出 ESLint](https://juejin.im/post/5bab946cf265da0ae92a75ca)
- [awesome-eslint](https://github.com/dustinspecker/awesome-eslint)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/prettier.svg">

### Prettier
</div>

> 什么是 Prettier：漂亮的代码格式化器；支持很多语言；被整合进绝大多数编辑器；极少的配置。
> 为什么要使用 Prettier：一保存代码就会自动格式化；使得整个团队的代码风格统一，减少不必要的代码 Review，节省时间和能量。


#### 知识点

1. 基本原理
2. 与编辑器整合
3. 与 Git Hooks 整合
4. 命令行使用
5. 与持续集成（CI）整合

#### 参考资源

- [Prettier 看这一篇就够了](https://zhuanlan.zhihu.com/p/81764012)
- [Prettier 介绍和基本用法](https://juejin.im/post/5ae91143f265da0ba60f97ea)
- [Prettier + ESLint 使用教程(译)](https://juejin.im/post/5d563ee551882506a87c7c2c)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/babel.svg">

### Babel
</div>

> Babel ，又名 Babel.js。 是一个用于 web 开发，且自由开源的 JavaScript 编译器、转译器。
> Babel 使软件开发者能够以偏好的编程语言或风格来写作源代码，并将其利用 Babel 翻译成 JavaScript（现今在浏览器最常用的编程语言）。
> Babel 是一个常用来使用最新的 JavaScript 语言特性的工具。身为一个转译器、或编译器，开发者可以使用 ECMAScript 6 以上的功能，并将其转换成旧版本等效的 JavaScript 让浏览器能够去解读。

#### 知识点

1. 基本原理
2. 与编辑器整合
4. 命令行使用
5. 与 Webpack 整合

#### 参考资源

- [Babel 中文网](https://www.babeljs.cn/docs/usage)
- [Babel 入门教程](http://www.ruanyifeng.com/blog/2016/01/babel.html)
- [Babel 7 教程](https://blog.zfanw.com/babel-js/)

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---



<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/webpack.svg">

### Webpack

</div>

> Webpack 是一个开源的前端打包工具。Webpack 提供了前端开发缺乏的模块化开发方式，将各种静态资源视为模块，并从它生成优化过的代码。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/stylelint.svg">

### StyleLint
</div>

> 强大的现代化检查器，可帮助您避免错误并在样式中强制执行约定。

<div align="center">🛠筹备中，敬请期待</div>

## 前沿概念

<div align="center">
<img style="display: inline;" width="100" height="100" style="padding-right: 10px;" src="./assets/images/material-ui.svg">
<img style="display: inline;" width="100" height="100" src="./assets/images/element.svg">

### 组件库
</div>

> 流行的React UI组件库/框架的集合，可帮助您为任何Web项目或应用程序构建出色的界面。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/typescript-icon.svg">

### TypeScript
</div>

> TypeScript是一种由微软开发的自由和开源的编程语言。它是JavaScript的一个严格超集，并添加了可选的静态类型和使用看起来像基于类的面向对象编程语法操作 Prototype。C#的首席架构师以及Delphi和Turbo Pascal的创始人安德斯·海尔斯伯格参与了TypeScript的开发。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/nextjs.svg">

### 服务端渲染
</div>

> SSR服务端渲染（英语：server side render）通常来说web页面的数据渲染都是由客户端或者浏览器端来完成的，先从服务器请求，然后到页面，再通过ajax请求到页面数据，之后把相应的数据填充到template模板形成完整的页面来呈现给用户。服务端渲染把数据的ajax请求放在了服务端，然后服务端把数据填充到template模板形成完整的页面，由服务端把渲染的完整的页面吐给客户端。这样减少了一次客户端到服务端的http请求，加快了相应速度，一般用于首屏的性能优化。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/microfrontend.svg">

### 微前端
</div>

> 与多个团队一起使用不同的JavaScript框架构建现代Web应用程序的技术，策略和方法。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/jest.svg">

### 测试
</div>

> 在软件测试中，自动化测试指的是使用独立于待测软件的其他软件来自动执行测试、比较实际结果与预期并生成测试报告这一过程。在测试流程已经确定后，测试自动化可以自动执行的一些重复但必要测试工作。也可以完成手动测试几乎不可能完成的测试。对于持续交付和持续集成的开发方式而言，测试自动化是至关重要的。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>

---

<div align="center">
<img style="display: inline;" width="100" height="100" src="./assets/images/docker.svg">

### 部署
</div>

> 将网站部署到云端，可以供互联网上的其他用户访问。

<div align="center">🛠筹备中，敬请期待</div>

<div align="center">
<br/>
<a href="#top">⬆️返回顶部</a>
</div>
