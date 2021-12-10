# Debian及Ubuntu系统下使其他程序开机启动的脚本

首先把addstart.py文件放入文件夹/usr/bin中，去掉后缀名变成addstart<br>
然后
```
sudo chmod 777 /usr/bin/addstart
```
就可以了
之后需要添加什么开机自启的程序的时候，直接命令行输入
```
sudo addstart
```
或
```
sudo su
addstart
```
反正就是要有sudo权限，不然开机服务写不进去<br>
然后就按照步骤走就行了。
