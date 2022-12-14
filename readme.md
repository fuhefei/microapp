## 一、项目要求

· 介绍小程序产品概念，引入小程序技术抽象。本周主要聚焦于在浏览器下实现小程序的双线程加载模型，了解 web-worker 相关的概念，实现基本的模块加载函数，并完成双线程的通信。

· 介绍基本的前端渲染框架概念，实现简单的基于 vdom 的渲染框架。

· 介绍编译 DSL 与渲染的关联，实现小程序支持的条件语句、循环语句和引用语句，支持基本的小程序 DSL。另外，实现几个基础的『原生组件』，并支持渲染。

· 最后将前几周的作品结合起来，构造小程序的渲染与逻辑抽象，支持小程序的『自定义组件』渲染与编写，能运行起来一个最简单的小程序应用。可拓展使用抖音云来托管小程序编译与分发服务。

## 成果介绍

#### 1）使用web-worker双线程加载，将渲染层发出的信息交给逻辑层处理，并在逻辑层处理后，将更改的内容返回。

#### 2）借鉴mini-react项目的部分内容，利用reactfiber实现类似react的vdom操作，实现类react的diff操作。

#### ~~3）(未实现)利用babel语法分析器，完成基于jsx的dsl中条件语句if、循环语句for的编译转换，再进行渲染。完成简单组件的封装。~~

#### 4）使用简单的语句小程序demo验证上述系统的正确性。


