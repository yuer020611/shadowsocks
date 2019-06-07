# How to use in linux ?

首先呢。我们得安装一下shadowsocks

其实呢，在linux系统里shadowsocks 就是一个软件包没有任何毛病。所以呢，我们需要将其下载安装。



获取软件包

TypeScript
git clone https://github.com/yuer020611/shadowsocks
image.png



打开包路径

TypeScript
cd shadowsocks
image.png







运行安装程序

TypeScript
python setup.py install
image.png





打开安装好的程序路径

TypeScript
cd shadowsocks
image.png

’



配置一个shadowsocks文件

TypeScript
sudo vim /etc/shadowsocks.json
image.png













配置格式：这个时候你需要输入改配置的服务器设置，除了有中文的地方要变，其他的基本上不变，因为其他的值都是默认值，如果你修改了默认值，那就请自己修改

TypeScript
{ 
"server":"95.179.184.226", 
"server_port":2019, 
"local_address": "127.0.0.1", 
"local_port":1080, 
"password":"yuer", 
"timeout":300, 
"method":"aes-256-cfb", 
"fast_open": false 
}
image.png







开始连接

TypeScript
 sslocal -c /etc/shadowsocks.json
image.png











下载谷歌浏览器插件                        ——> URL : https://pan.baidu.com/s/1Wnj6Pp-ZLYFabfjDIvexpg  提取码75vs

按照图中所示方法即可

image.png









然后访问谷歌试试，这激动人心的画面，对你成功了

image.png
