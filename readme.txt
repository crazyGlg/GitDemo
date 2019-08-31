之前在网找了好多方法，可是都解决不了，很多人在在Environment里添加set LANG=zh_CN.UTF-8来解决中文乱码的问题，可是我用这个方法并没有成功，可能是环境的原因吧，我的系统是win10的。
最后找到解决办法：
Settings->Startup->Environment 添加
set LANG=zh_CN.UTF-8
set LC_ALL=zh_CN.utf8
glg