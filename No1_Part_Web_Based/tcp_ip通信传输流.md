## TCP/IP通信传输流
> 利用TCP/IP协议族进行网络通信时，会通过分层顺序与对方新型通信。    
> 发送端从应用层往下走，接收端则往应用层上走。

### example【HTTP】
> HTTP举例说明如下：    

首先作为发送端的客户端在应用层（HTTP协议）发出一个想看某个web页面的HTTP请求。    
接着，为了传输方便，在传输层（TCP协议）把从应用层处收到的数据（HTTP报文）进行分割，并在各个报文上标记序号及端口号转发给网络层。    
在网络层（IP协议），增加作为通信目的地的MAC地址后转发给链路层。这样一来，发往网络的通信请求就准备齐全了。    

接收端的服务器在链路层接收到数据，按序往上层发送，一直到应用层。    
当传输到应用层，才能算真正接收到客户端发送来的HTTP请求。

发送端载层与层之间传输数据时，每经过一层必定会被打上一个该层所属的首部信息。    
反之，接收端在层与层传输数据时，每经过一层时会把对应的首部消去。    
这种把数据信息包装起来的做法称为封装（encapsulate）。
