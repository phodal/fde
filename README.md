# Awesome 前端效能

目录：


 
## 1. 设计


### 原型设计

相关资源：

 - Balsamiq Mockups
 - Axure
 - Sketch

### 可视化搭建前端

Why：

> 

How：

示例：

 - [飞冰](https://github.com/alibaba/ice) 是一套综合解决方案，用来极速构建中后台应用。

相关文章：

### 设计系统（Design System）

目的（Why）：

> **设计系统**是一组相互关联的设计模式与共同实践的，以连贯组织来达成数字产品的目的。模式是重复组合以创建界面的元素：用户流、交互、按钮、文本、图标，颜色、排版、微观等。实践则是选择创建，捕获，共享和使用这些模式的方法，特别是在团队中工作时。 —— Alla Kholmatova 《Design Systems》

如何做：

示例：

 - [Material Design](https://material.io/design/)
 - [Ant Design](https://ant.design/)

相关模式：

 - **原子设计**，是一个设计方法论，由五种不同的阶段组合，它们协同工作，以创建一个有层次、计划性的方式来界面系统。

相关文章：

 - [What is a Design System?](https://medium.muz.li/what-is-a-design-system-1e43d19e7696)
 - [Atomic Design](http://atomicdesign.bradfrost.com/table-of-contents/)

### Design System Ops

Why：

> **Design System Ops**，允许整个组织的人员设计、重新设计和改进产品，而不会失去质量，可用性和一致性。

相关文章：

 - [DesignOps at Airbnb: How we manage effective design at scale](https://airbnb.design/designops-airbnb/)
 - [DesignOps: Unleashing the potential of our design studio](https://www.atlassian.com/blog/inside-atlassian/designops-atlassian-design-studio)
 - [What is design operations and why should you care?](https://medium.com/designer-hangout/what-is-design-operations-and-why-should-you-care-b72f02b47761)

## 2. 创建

### 脚手架

>  **脚手架**。作为一个基础的模块应用，用于快速生成、搭建前端应用。它除了包含一个前端项目所需要的要素，往往还包含着组织内部相关的规范和模式，如部署模板、构建系统等。

类型：

 - GUI 脚手架。
 - CLI 脚手架。

相关文章：

 - [How to build your own React boilerplate](https://medium.freecodecamp.org/how-to-build-your-own-react-boilerplate-2f8cbbeb9b3f)

### 快速工作平台

Why：搭建环境不是一件容易的事。

>

How：通过 CLI 生成。

## 3. 开发 

### 代码模式库

> 模式库，是一系列可复用代码的合集，如前端的组件，通用的工具函数等等。其目的是在多个应用之间共享代码，以降低修改成本。在设计架构的时候，要是考虑内建相应的 UI 组件库，便需要考虑结合装饰器模式，作为一层代理，来封装外部的 API，以降低后期的修改成本。它还包含了用于多个前端应用通讯的**数据通讯**库。


相关资源：[Vanilla.js Boilerplates](https://vanillajstoolkit.com/boilerplates/)

相关文章：
 
 - [Creating your own vanilla JS helper library like Lodash and Underscore.js](https://gomakethings.com/creating-your-own-vanilla-js-helper-library-like-lodash-and-underscore.js/)
 - [How to create your own vanilla JS DOM manipulation library like jQuery](https://gomakethings.com/how-to-create-your-own-vanilla-js-dom-manipulation-library-like-jquery/)

### Mock Server

Why：

> Mock Server（仿造服务器），即用于仿造后端接口的模拟 HTTP 服务器。它是一个简单的 HTTP 服务，在后端未准备好的情况下，它可以为前端提供一个可用的 API 服务。

模式：

 - **普通 Mock Server**。在 API 配置文件中定义了什么，便返回什么内容。
 - **DSL 形式的 Mock Server**。它是以普通的 Mock Server 有所不同，其中的配置文件（通常是 JSON）是通过特定格式编写的，返回的数据只是 API 配置的一部分。
 - **编程型 Mock Server**。它需要我们编写简单的代码，才能返回对应的 API 数据。它的优点是灵活性更高，但是缺点便是维护成本更高。
 - **契约测试**，又称之为消费者驱动的契约测试（Consumer-Driven Contracts，简称 CDC），是指从消费者业务实现的角度出发，驱动出契约，再基于契约，对提供者验证的一种测试方式。

相关资源：

 - [Faker.js](https://github.com/marak/Faker.js/)
 - [Swagger](https://github.com/swagger-api/swagger-ui)
 - [Moco](https://github.com/dreamhead/moco)

### 编辑器/IDE 插件

> 编辑器/IDE 插件，用于在 IDE/编辑器插件中，集成文档、常用代码等相关内容。

Intellij IDEA 相关资源：

 - [Creating Your First Plugin](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started.html)
 - [Creating a Plugin Project](https://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/creating_plugin_project.html)

 VisualCode Studio 相关资源：

  - [Your First Extension](https://code.visualstudio.com/api/get-started/your-first-extension)
  - [Snippet Guide](https://code.visualstudio.com/api/language-extensions/snippet-guide)

### 浏览器插件

相关类型：

 - 

### 性能工具

## 4. 联调

### 统一 UI 接口

### 自动化契约测试

Why: 在实施前后端分离架构的过程中，最让人苦恼的莫过于：API 发生了变化。API 发生变化的原因那可是相当的丰富：业务变化、字段名出错、第三方接口不匹配等等。

> 

相关资源：

 - [前后端分离：使用 mest 做契约测试跟踪 API 接口变更](https://www.phodal.com/blog/frontend-contract-test-use-mest-way/)

## 5. 测试

### E2E 测试

## 6. 部署



## 7. 运营


### 错误日志跟踪

Why:

> 

How：

相关文章：

 - [前端代码异常监控实战](https://github.com/happylindz/blog/issues/5)

## 其它 

### 相关文章

**效能**：

 - [十倍效能提升——Web 基础研发体系的建立](http://www.cnblogs.com/sskyy/p/8613393.html)

**度量**

 - [如何衡量研发效能？阿里资深技术专家提出了5组指标](https://yq.aliyun.com/articles/690725)。关键字：持续发布能力、需求响应周期、交付吞吐率、交付过程质量、对外交付质量。

### 相关资源

### AlloyTeam

来源：[https://github.com/Pines-Cheng/think/issues/32](https://github.com/Pines-Cheng/think/issues/32)

AlloyTeam 内部都有对应的解决方案：

 - Steamer 命令行工具及脚手架
 - AlloyStore 组件展示平台
 - LinkStar 假数据联调平台
 - JB 测试部署平台
 - Ars 发布上线平台
 - AlloyData 数据上报平台
 - Sentry 错误监控平台
 - AlloyKit 离线包发布平台
 - XuanWu 直出平台

License
---

[![Phodal's Idea](http://brand.phodal.com/shields/idea-small.svg)](http://ideas.phodal.com/)

© 2019 A [Phodal Huang](https://www.phodal.com)'s [Idea](http://github.com/phodal/ideas).  This code is distributed under the MIT license. See `LICENSE` in this directory.
