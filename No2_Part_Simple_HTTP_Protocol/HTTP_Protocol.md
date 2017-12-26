## HTTP协议
> HTTP协议和TCP/IP协议族内的其他众多协议相同，用于客户端和服务器之间的通信
### 通过请求和响应的交换达成通信
```
GET /index.htm HTTP/1.1
Host:hackr.jp
```
#### 请求报文
> 由请求方法、请求URI、协议版本、可选的请求首部字段和内容实体构成的
```
POST /form/entry HTTP/1.1

Host: hackr.jp
Connection: keep-alive
Content-Type: application/x-www-form-urlencoded
Content-Length: 16

name=ueno&age=37
```
#### 响应报文
> 由协议版本、状态码、用以解释状态码的原因短语、可选的响应首部字段以及实体主体构成
```
HTTP/1.1  200  OK

Date: Tue, 10 Jul 2012 06:50:15 GMT
Content-Length:  362
Content-Type: text/html

<html>
......
```
### HTTP是不保存状态的协议
> 无状态(stateless)协议
