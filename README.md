# Re0-

从一个啥都不懂的小白，变成了一个要去学校学习相关专业的啥都不懂的小白。

-
21.8.27
* 一个makefile花了三天才明白，编译好的exe在linux里用terminal打开的
* 但是这个东西怎么样才能连接到http端口或者做成个服务器？
* 顺着 Linux C++ http服务器的方向看了一些东西
* 大致归类 有简单实现http 自己写一个http.h 底层是socket  socket是啥？
* 有说的长远的说要学习UNIX高级编程APUE、UNP 不过在这之前好像还要再仔细学一遍OS和计组
* 借用git上一个开源框架workflow 框架又是什么？ workflow在windows上安装并不顺利
* 按照指引安装了Cmake和openssl 但是workflow没弄好 powershell没法识别cmake和openssl指令
* 按照workflow的描述安装后会得到一个vs工程 但是这个工程又如何套在farsite上呢
* 进展缓慢
* 再看看workflow 明天试试自己写 还有socket又是什么。
-
21.8.28
* 今天收获颇多
* 沿着昨天的思路试着自己写了一下http.h 发现目前自己是在vs上进行g++的工作 socket（Winsock2.h） TcpClient都不支持（或者说是win平台下的支持而非Linux
* 然后又去虚拟机里看了看vscode 这个好像可以 但是在vscode直接编译还是有点不对劲
* 以后决定还是vscode编辑文本不作为编译运行的主力
* 接着说一说http服务器的进展，简而言之就是利用socket提供的函数接口来操作信息收发回复 具体收发顺序 就是计网里的握手
* 但是又多了新问题
* 1.还是没有找到支持TcpClient的头文件或者是功能
* 2.能不能支持我在visual studio上写这些（socket有winsock2
* 3.写好了如何编译运行
* 4.如何把workflow装上
-
