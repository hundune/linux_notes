# 找回root密码

启动Linux时，移动光标选择核心态（core）。按 e 

找到linux16……UTF-8 ，在后面输入init=/bin/sh

进入单用户模式

输入mount -o remount/ 后按回车

输入passwd

输入密码，确认密码（不能使用小键盘）

touch /.autoreable 回车

exec /sbin/init 回车(时间较长，完成后会重启，生效)

