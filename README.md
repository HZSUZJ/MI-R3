# MI-R3
小米路由器3（三）刷老毛子固件

## 声明 
刷机后果，自行承担

## 刷机准备 
路由器插好网线，插好电源，一切步骤都是在连接wifi下 
下面是三个文件
https://pan.baidu.com/s/1ygZUfvbnDbBA8T1rpqlelQ<br>
提取码：2q99

## 正式步骤
1.在miwif后台管理界面中，手动升级固件，选择miwifi.bin

2.利用虚拟机开启ssh

3.等菜单出来后，输入数字0（不要用小键盘）

4.蹦出路由器管理ip，直接回车

5.输入路由器登录密码，回车

6.输入回车进入主菜单

7.输入4

8.再输入4 写入固件

9.选n回车

10.选y重启

11.等会会有个华硕的wifi是asus 连接密码1234567890

12.然后浏览器输入192.168.1.1 账号密码都是admin

13.按照我image1中操作选择MI-3_3.4.3.9-099固件升级

14.按照我image2中的操作，顺序重置下

## 随笔
管理地址是 192.168.123.1 账号密码都是 admin<br>
在外部网络，修改成pppoe协议，然后设置拨号信息就可以拨号上网了<br>
不是拨号的默认就可以<br>
wifi是pdcn 密码1234567890

接下来你就可以自己捣鼓你的路由器，科学上网，屏蔽广告等
