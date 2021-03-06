## 与 HTTP 关系密切的协议
> 在 TCP/IP 协议族中与 HTTP 密不可分的3个协议
> + IP
> + TCP
> + DNS

### 负责传输的IP协议
    按层次分，IP(Internet Protocol)网际协议位于网络层。几乎所有使用网络的系统都会用到IP协议。
    IP协议的作用是把各种数据包传送给对方。
    
    要保证传送至目的地，两个重要条件
    - IP地址
    - MAC地址(Media Access Control Address)
    
    使用ARP协议凭借MAC地址进行通信。
    ARP（Address Resolution Protocol）
    是一种用以解析地址的协议，根据通信方的IP地址就可以反查出对应的MAC地址。
   
    

### 确保可靠性的TCP协议         
    按层次分，TCP位于传输层，提供可靠的字节流服务    
    TCP协议为了更容易传达大数据才把数据分割，而且TCP协议能够确认数据最终是否送达到对方。
    
    三次握手确保数据能够到达目标
        - 发送端首先发送一个带SYN标志的数据包给对方
        - 接收端收到后回传一个带有SYN/ACK标志的数据包以示传达确认信息
        - 最后，发送端再回传一个带ACK标志的数据包，代表“握手”结束。

### 负责域名解析的DNS服务    
    DNS(Domain Name System)服务是和HTTP协议一样位于应用层的协议    
    它提供域名到IP地址之间的解析服务    
    
    
