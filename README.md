# docker_nps
nps⁠的服务端

一款轻量级、功能强大的内网穿透代理服务器。支持tcp、udp流量转发，支持内网http代理、内网socks5代理，同时支持snappy压缩、站点保护、加密传输、多路复用、header修改等。支持web图形化管理，集成多用户模式。

使用方式

docker pull ffdfgdfg/nps

下载conf文件夹⁠并解压，或前往项目主页⁠自行下载**(升级请忽略)**

继续阅读文档⁠修改配置文件**(升级请忽略)**

启动：docker run -d --name nps --net=host -v <本机conf目录>:/conf ffdfgdfg/nps

请确保为conf文件夹

查看日志docker logs nps
