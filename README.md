# Awesome 前端效能提升

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

#### GUI 脚手架  

#### CLI 脚手架

## 3. 开发 

### 代码模式库

### Mock Server

Why：

> Mock Server（仿造服务器），即用于仿造后端接口的模拟 HTTP 服务器。它是一个简单的 HTTP 服务，在后端未准备好的情况下，它可以为前端提供一个可用的 API 服务。

模式：

 - **普通 Mock Server**。在 API 配置文件中定义了什么，便返回什么内容。
 - **DSL 形式的 Mock Server**。它是以普通的 Mock Server 有所不同，其中的配置文件（通常是 JSON）是通过特定格式编写的，返回的数据只是 API 配置的一部分。
 - **编程型 Mock Server。它需要我们编写简单的代码，才能返回对应的 API 数据。它的优点是灵活性更高，但是缺点便是维护成本更高。
 - **契约测试**，又称之为消费者驱动的契约测试（Consumer-Driven Contracts，简称 CDC），是指从消费者业务实现的角度出发，驱动出契约，再基于契约，对提供者验证的一种测试方式。

相关资源：

 - [Faker.js](https://github.com/marak/Faker.js/)
 - [Swagger](https://github.com/swagger-api/swagger-ui)
 - [Moco](https://github.com/dreamhead/moco)

### 编辑器/IDE 插件


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

### 相关资源

License
---

[![Phodal's Idea](http://brand.phodal.com/shields/idea-small.svg)](http://ideas.phodal.com/)

© 2019 A [Phodal Huang](https://www.phodal.com)'s [Idea](http://github.com/phodal/ideas).  This code is distributed under the MIT license. See `LICENSE` in this directory.
