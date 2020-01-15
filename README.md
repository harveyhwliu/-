# 目的
&emsp;&emsp;收集、汇总、总结一些知识点<br/>

### 日志系统:
&emsp;&emsp;日志分为同步日志和异步日志，通常都会采用同步日志，但是同步日志的QPS通常不会很高，高性能情况下需要考虑异步日志:<br/>
   - C++
      - g3log:G3log 是一个开源、支持跨平台的异步 C++ 日志框架，支持自定义日志格式。基于 g2log 构建，提升了性能，支持自定义格式。


### API文档工具:
&emsp;&emsp;网站架构基本都由原来的后端渲染，变成了：前端渲染、前后端分离的形态，前端和后端的唯一联系，变成了API接口；API文档变成了前后端开发人员联系的纽带，变得越来越重要:<br/>
   - swagger:
      - Swagger 是一种 Rest API 的 简单但强大的表示方式，标准的，语言无关，这种表示方式不但人可读，而且机器可读。 可以作为 Rest API 的交互式文档，也可以作为 Rest API 的形式化的接口描述，生成客户端和服务端的代码。 Swagger 主要包括三部分 Swagger API Spec，描述 Rest API 的语言。Swagger UI，将 Swagger API Spec 以 HTML 页面展现出来的模块。Swagger Editor，Swagger API Spec 的编辑器。这里不描述 Editor.<br/>
   - RAP 
      - RAP 是一个 GUI 的 Web 接口管理工具。在 RAP 中，可以定义接口的 URL、请求&响应细节格式等等。同时 RAP 还提供 MOCK 服务、测试服务等自动化工等工具，帮助开发团队高效开发。
