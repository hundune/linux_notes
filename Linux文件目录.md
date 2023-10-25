# Linux文件目录

在linux中所有的都是文件（硬件也会被映射为文件）

![1698113004442](C:\Users\86182\AppData\Roaming\Typora\typora-user-images\1698113004442.png)

/ ：顶级目录

root：为系统管理员，超级权限者的用户目录

home：存放普通用户的主目录，每一个用户都有一个目录

bin：常用指令

etc：系统管理的配置文件，比如mysql

usr：用户安装的程序默认安装在这，如同win的programfile

boot：linux的启动文件

mnt：将外部的文件系统挂载（额外加一个硬盘……）

opt：给主机额外安装软件所存放的目录，如安装Oracle数据库就可以放到该目录下，默认为空

/usr/local：这时另一个给主机额外安装的目录，一般是通过编译源码方式安装的程序

opt与usr/local的区别：opt是安装的文件下载到的地方（程序安装包）usr/local是安装的时候放的地方（程序解压文件）

/var：不断扩充的东西，习惯将经常修改的目录放在这个目录下，包括各种的日志文件

