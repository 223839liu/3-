# 第一节课
## 协议 protocol
[![1.jpg](https://i.postimg.cc/G35Bbhpc/1.jpg)](https://postimg.cc/XX9N8WFh)
应用层：用户经常接触到的，常见的：HTTP（80），HTTPS（443）,FTP(21),DNS(53),
DHCP(68),Telent(23),Smtp(25),SSH(22)<br>
表示层：数据加解密，数据解压缩，图片/视频编解码<br>
会话层：session会话管理，服务器验证用户登录，断点传<br>
传输层：TCP,UDP,线程，端口，socket<br>
网络层：防火墙，寻址，路由转发,ip,ARP,RARP<br>
数据链路层：交换机，网卡<br>
物理层：光缆<br>
---
[![1.png](https://i.postimg.cc/GmqwyvdW/1.png)](https://postimg.cc/ZWBMkB9H)
架构对比
**C/S:Client/Server**
**B/S:Browser/server**
1.C/S有专门的客户端，B/S没有专门的客户端
2.C/S可以使用任意的协议，常用的是TCP和UDP协议，B/S只能使用HTTP和HTTPS协议
---
[![QQ-20240611100016.png](https://i.postimg.cc/yxzr5N7h/QQ-20240611100016.png)](https://postimg.cc/XGQ8B4GX)
动态库： 节省内存空间，修改时只需要编译动态库，不需要重新编译可执行文件
静态库：调用速度快，可以直接移值，缺点：浪费应用空间
先接收信息的叫服务端
发送时IP决定发给哪个设备，端口号决定发给哪个程序
---
# 第二节课

