## URI 和 URL
> URI (Uniform Resource Identifier，统一资源标识符)    
> URL (Uniform Resource Locator，统一资源定位符)
### 统一资源标识符
#### Uniform
> 规定统一的格式可方便处理多种不同类型的资源，而不用根据上下文环境来识别资源指定的方式    
> 另外，加入新增的协议方案(如http:或ftp:)也更容易
#### Resource
> 资源的定义是“可标识的任何东西”    
> 不仅是文档文件，图像或服务(例如当天的天气预报)等能够区别于其他类型的，全都可以作为资源    
> 另外资源不仅可以是单一的，也可以是多数的集合体
#### Identifer
> 表示可标识的对象。也称为标识符

URI就是由某个协议方案表示的资源的定位标识符。协议方案是指访问资源所使用的协议类型名称    
采用HTTP协议时，协议方案就是http。除此之外，还有ftp、telnet、mailto、file等

URI用字符串标识某一互联网资源    
URL表示资源的地点(互联网上所处的位置)    
URL是URI的子集
### URI格式
> 使用http:或https:等协议方案名获取访问资源时要指定协议类型。不去分字母大小写，最后附一个冒号(:)    

http://user:pass@www.example.jp:80/dir/index.htm?uid=1#ch1    
协议方案名---登录信息(认证)---服务器地址---服务器端口号---带层次的文件路径---查询字符串---片段标识符    
