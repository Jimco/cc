# 1. HTTP

Http 定义了与服务器交互的不同方法，最基本的方法有 4 种，分别是 `GET、POST、PUT、DELETE`。URL 全称是资源描述符，我们可以这样认为：一个 URL 地址，它用于描述一个网络上的资源，而 HTTP 中的 `GET、POST、PUT、DELETE` 就对应着这个资源的 `查、该、增、删` 4个操作。

在传统的模式，用户请求的生命周期如下：

1. 浏览器发送一个 HTTP 请求到 Web 服务器。
2. Web 服务器解析请求，然后读取数据存储层，制定一个 HTML 文件，并用一个 HTTP 响应把它发送到客户端。
3. HTTP 响应通过互联网传送到浏览器。
4. 浏览器解析 Web 服务器的响应，使用 HTML 文件构建了一个的 DOM 树，并且下载引用的 CSS 和 JavaScript 文件。
5. CSS 资源下载后，浏览器解析它们，并将它们应用到 DOM 树。
6. JavaScript 资源下载后，浏览器解析并执行它们。