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
----
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
----
### 6.3.2 Connection
#### 控制不再转发给代理的首部字段
#### 管理持久连接
----
### 6.3.3 Date
----
### 6.3.4 Pragma
----
### 6.3.5 Trailer
----
### 6.3.6 Transfer-Encoding
----
### 6.3.7 Upgrade
---
### 6.3.8 Via
---
### 6.3.9 Warning
---

## 6.4 请求首部字段
### 6.4.1 Accept
#### 文本文件
#### 图片文件
#### 视频文件
#### 应用程序使用的二进制文件
---
### 6.4.2 Accept-Charset
---
### 6.4.3 Accept-Encoding
#### gzip
#### compress
#### deflate
#### identity
---
### 6.4.4 Accept-Language
---
### 6.4.5 Authorization
    401
---
### 6.4.6 Expect
    417
---
### 6.4.7 From
---
### 6.4.8 Host
---
### 6.4.9 If-Match
    412
---
### 6.4.10 If-Modified-Since
    304
---
### 6.4.11 If-None-Match
---
### 6.4.12 If-Range
    412
---
### 6.4.13 If-Unmodified-Since
    412
---
### 6.4.14 Max-Forwards
---
### 6.4.15 Proxy-Authorization
---
### 6.4.16 Range
---
### 6.4.17 Referer
---
### 6.4.18 TE
---
### 6.4.19 User-Agent
---
## 6.5 响应首部字段
### 6.5.1 Accept-Ranges
----
### 6.5.2 Age
----
### 6.5.3 ETag
#### 强ETag
#### 弱ETag
----
### 6.5.4 Location
----
### 6.5.5 Proxy-Authenticate
----
### 6.5.6 Retry-After
----
### 6.5.7 Server
----
### 6.5.8 Vary
----
### 6.5.9 WWW-Authenticate
----
## 6.6 实体首部字段
### 6.6.1 Allow
    405
----
### 6.6.2 Content-Encoding
----
### 6.6.3 Content-Language
----
### 6.6.4 Content-Location
----
### 6.6.5 Content-MD5
----
### 6.6.6 Content-Range
----
### 6.6.7 Content-Type
----
### 6.6.8 Content-Length
----
### 6.6.9 Expires
----
### 6.6.10 Last-Modified
----
