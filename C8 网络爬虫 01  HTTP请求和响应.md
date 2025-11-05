# HTTP

HTTP（Hypertext Transfer Protocol），译为超文本传输协议，是一种客户端和服务器之间的请求-响应协议

### 方法类型

·GET方法：获得数据

·POST方法：创建数据

### HTTP请求

**请求行**

POST/user/info ？HTTP/1.1

方法类型/资源路径？查询参数   协议版本

**请求头**

Host:www.example.com

主机域名

User-Agent:curl/7.77.0

告知服务器客户端的相关信息

Accept:*/*

告知服务器客户端想接受的响应数据的类型

如：

html:text/html

json:application/json

json/html:text/html,application/json

任意类型*/*

**请求体：**

{"username":"wangzichuan",

  "email":"wangzichuan@mail.ustc.edu"}

### HTTP响应

**状态行**

HTTP/1.1 200 OK

协议版本/状态码/状态消息

200 OK

301 Moved Permanently

400 Bad Request

401 Unauthored

403 Forbidden

404 Not Found

500 Internal Server Error

503 Server Unavailable

**响应头**

Data:Tue,4 Nov 2025 14:33:30 GMT

Content-Type:text/html; charset=utf-8

日期，返回类型和编码

**响应体**

服务器返回的内容
