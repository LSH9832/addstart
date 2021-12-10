# Debian及Ubuntu系统下使其他程序开机启动的脚本

首先把addstart.py和adddesktopstart.py文件放入文件夹/usr/bin中，去掉后缀名变成addstart和adddesktopstart<br>
然后
```
sudo chmod 777 /usr/bin/addstart
sudo chmod 777 /usr/bin/adddesktopstart
```
就可以了
之后需要添加什么开机自启的程序的时候，直接命令行输入
```
sudo addstart           # 如果只是后台服务用这个
sudo adddesktopstart    # 如果这个程序涉及到图形界面用这个
```
或
```
sudo su
addstart    # 或adddesktopstart
```
反正就是要有sudo权限，不然开机服务写不进去<br>
然后就按照步骤走就行了。
