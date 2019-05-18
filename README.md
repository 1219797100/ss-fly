一键脚本安装shadowsocks/shadowsocksR/V2Ray + 开启bbr
---

一键脚本搭建shadowsocks/shadowsocksR/V2Ray + 设置开启自启动 + 升级内核&开启bbr加速。

## 支持系统
CentOS 6+

Debian 7+

Ubuntu 12+

## 使用教程
一键搭建ss/ssr：[一键脚本搭建shadowsocks+开启bbr](http://suniceman.com/2019/04/10/install-shadowsocks-in-one-command/)

##指南
1、-bash：ss-fly/ss-fly.sh：Permission denied
解决办法：
因为用户没有权限，而导致无法执行。用命令chmod 修改一下bin目录下的.sh权限就可以了。

chmod u+x *.sh

这里的u 这里指文件所有者，+x 添加可执行权限，*.sh表示所有的sh文件（该指令在ss-fly文件夹内执行）
