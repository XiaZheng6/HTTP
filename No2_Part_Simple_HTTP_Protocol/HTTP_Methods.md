## HTTP 方法
### GET
> 获取资源
### POST
> 传输实体主体

### GET 与 POST区别
> 据说get由长度限制？其实没有，因为长度限制是浏览器做的，和http协议无关    
> 据说get不安全，post安全？其实没有，因为http都是明文传输，get的数据在url里，post的数据在http的body体里    
> 区别在于get是幂等的，调用多少次，造成的结果都是一样的。post不是幂等

### PUT
> 传输文件
### HEAD
> 获得报文首部
### DELETE
> 删除文件
### OPTIONS
> 询问支持的方法
### TRACE
> 追踪路径
### CONNECT
> 要求用隧道协议连接代理
