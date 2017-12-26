# 6 HTTP首部
> HTTP协议的请求和响应报文中必定包含HTTP首部
## 6.1 HTTP报文首部
* HTTP请求报文
    + 报文首部
    + 空行
    + 报文主体
    
  在请求中，HTTP报文首部由方法、URI、HTTP版本、HTTP首部字段构成
----
* HTTP响应报文
    + 报文首部
    + 空行
    + 报文主体
    
  在响应中，HTTP报文首部由HTTP版本、状态码（数字和原因短语）、HTTP首部字段构成
----
## 6.2 HTTP首部字段
> HTTP首部字段是由首部字段名和字段值构成的，中间用冒号":"分隔
### HTTP首部字段类型
#### 通用首部字段
#### 请求首部字段
#### 响应首部字段
#### 实体首部字段
## 6.3 HTTP/1.1 通用首部字段
### 6.3.1 Cache-Control
#### public
#### private
#### no-cache
#### no-store
#### s-maxage
#### max-age
#### min-fresh
#### max-stale
#### only-if-cached
#### must-revalidate
#### proxy-revalidate
#### no-transform
#### cache-extension token
### 6.3.2 Connection
