# Easy-SSR-Bash-Python-The-Final
一个ShadowsocksR多用户管理Shell脚本（基于官方mujson版本），集成SSR多用户管理，流量限制，加密更改等基本操作。是一个基于ShadowsocksR官方的mujson的辅助脚本。方便用户操作。


## 系统支持 ##

 - Ubuntu 14
 - Ubuntu 16
 - Debian 7
 - Debian 8
 - CentOS 6
 - CentOS 7

## 功能 ##

 - 一键开启、关闭SSR服务
 - 添加、删除、修改用户端口和密码
 - 自由限制用户端口流量使用
 - 自动修改防火墙规则
 - 自助修改SSR加密方式、协议、混淆等参数
 - 自动统计，方便查询每个用户端口的流量使用情况
 - 自动安装Libsodium库以支持Chacha20等加密方式

## 缺点 ##

 - 无法删除最后一名用户（官方限制）

## 安装 ##
###CentOS系列

    yum update -y && yum install unzip zip -y && yum install wget -y && wget -N --no-check-certificate https://raw.githubusercontent.com/Moexin/Easy-SSR-Bash-Python-The-Final/master/ssr.zip && unzip ssr.zip && cd SSR* && bash install.sh

###Debian/Ubuntu系列

    apt-get update -y && apt-get install unzip zip -y && apt-get install wget -y && wget -N --no-check-certificate https://raw.githubusercontent.com/Moexin/Easy-SSR-Bash-Python-The-Final/master/ssr.zip && unzip ssr.zip && cd SSR* && bash install.sh

## 卸载 ##

    cd /root/SSR-Bash-Python-The-Final && bash uninstall.sh

## 自检 ##

    cd /root/SSR-Bash-Python-The-Final && bash self-check.sh



