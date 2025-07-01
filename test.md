## 1.ubuntu和windows 时钟问题
在Windows下启用UTC

### 1.打开运行窗口（快捷键Win+R），然后输入regedit启动注册表编辑器，并找到一下目录位置：
>HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Control/TimeZoneInformation/

### 2.安装 vim：
>sudo apt update && sudo apt install vim`
>sudo yum install vim `                   

### 3.在Ubuntu下关闭UTC
>sudo vim /etc/default/rcS`
