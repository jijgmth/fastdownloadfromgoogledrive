# dlfromgoogledrive
This project will show you how to quickly download files from googledrive

首先需要准备SS代理工具（一个github上开源的科学上网插件）和IDM多线程下载工具

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image1.png)

shadowsocks最新发布版本下载地址：https://github.com/shadowsocks/shadowsocks-windows/releases ，点击下载zip包解压即可

打开之后的界面

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image2.png)

这个时候还是没有代理服务器线路的，我们需要从网上获取一些免费的线路来用，当然你也可以自己搭建，具体搭建方法自行Google或者百度

下面是一个比较好的免费ss线路分享网站：

https://free-ss.site/

大陆地区打不开，需要修改hosts文件，具体操作方法为

![image](https://free-ss.site/v/direct_access.png)

然后查看最新的分享列表，找到左侧评分较高的链接（优先选择US（美国）的线路，这样下载体验会更好），将对应的IP地址、端口号、密码、加密方式依次填入shadowsocks界面中，然后保存，最后按照下图所示启动代理，然后打开浏览器尝试进入Google、YouTube等网站，如果能正常打开就说明这条线路是有效的，否则需要重新更换其他线路

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image4.png)

至此，shadowsocks的部分就算配置完成了

接下来配置IDM，IDM需要下载破解版，下载地址请自行上网搜索，下载完成后需要进行配置（不同版本的IDM配置界面可能会有一些不一样，但是这些选项都有）

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image5.png)
![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image6.png)
![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image7.png)

最后，需要在浏览器中安装一个扩展插件，这个插件的作用是接管浏览器的下载事件，就是原本是浏览器下载的改用IDM进行下载

一般在下载好的IDM文件夹里面可以找到如下图这个.crx格式的文件，这个就是浏览器扩展的安装包，将这个安装包拖到浏览器窗口中就可以实现安装

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image8.png)

提醒一句，Chrome浏览器有可能会因为插件来源不明而导致无法正常安装，如果出现这个情况请选择360系列的浏览器，下面以360极速浏览器为例，插件拖进去之后添加扩展，然后需要手动进入扩展中心，找到对应的扩展插件，然后勾选启用，记住底下的在隐身模式中启用和允许访问文件网址务必勾选上否则可能无法正常唤起IDM，Chrome浏览器同理

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image9.png)

最后，在安装好插件的浏览器中打开Googledrive的分享链接，点击右上角的下载按钮，正常来说应该会唤起IDM的下载界面

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image10.png)
![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image11.png)

接下来就可以享受高速的下载体验了，你的下载速度取决于你在shadowsocks中使用的线路的好坏

注意：当某个googledrive档案的下载人数过多时会提示资源下载超额，需要等待24小时以后才可下载的提示，出现这个问题请参考以下方法进行破解（需要自行注册一个Google账号）

![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image12.png)
![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image13.png)
![image](https://github.com/jijgmth/dlfromgoogledrive/blob/master/image/image14.png)

IDM是一款非常优秀的多线程下载工具，学会使用这款工具可以给你的下载带来很多不一样的体验，更多用法可以自行上网搜索
