# NetKeeperDialer

![NetKeeper](https://github.com/lmgy/NetKeeperDialer/blob/master/readme/0.jpg)  
截取NetKeeper拨号时的真实账号，并自动post到路由器，实现路由器上网。  

CQUPT,TP-Link TL-WR842N测试可以使用。

软件下载地址：[NetKeeperDialer-1.0](https://github.com/lmgy/NetKeeperDialer/releases/download/1.0/NetKeeperDialer-Release.zip)

## 使用方法

1. 使用创翼的**4.7.9.589**版本（其他版本未测试）
2. 打开创翼，但不登录
3. 打开本软件，在设置里面填好相关内容，然后点击“开始截取”，此时程序可能会假死，正常情况
4. 登录创翼，如果正常，会截取到真实的账号并自动提交到路由器，并且自动验证是否能联网
5. 创翼会显示联网失败，不用管它，直接关闭，本软件也关闭

## Ps

1. 使用了MetroModernUI.1.4.0.0，没有的自己在NuGet里添加。
2. 如果不能用，可能是创翼客户端的问题或者是路由器的问题，目前只试过**TP-Link TL-WR842N**，其他型号路由器可以自己去抓包，然后自己写。
3. 目前最新版本的创翼无法使用，请使用**4.7.9.589**版本
4. 创翼会自动更新，可以删除创翼目录下的**update.exe**

创翼**4.7.9.589**版本下载链接：[https://github.com/lmgy/NetKeeperDialer/blob/master/windows589.rar](https://github.com/lmgy/NetKeeperDialer/blob/master/windows589.rar)