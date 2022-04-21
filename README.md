# Linux-NetSpeed
本脚本已不更新，推荐使用5.5以上内核自带的bbr速度最佳
- https://roov.org/2020/03/bbr-bbrplus-bbr2/
- 推荐使用该脚本：bash <(curl -Lso- https://git.io/kernel.sh)
```
先安装 wget环境
yum -y install wget    ##ContOS Yum 安装 wget
apt-get install wget   ##Debian Ubuntu 安装 wget

wget -N --no-check-certificate "https://raw.githubusercontent.com/brozh85/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
秋水逸仙
wget -N --no-check-certificate "https://github.com/ylx2016/Linux-NetSpeed/releases/download/sh/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
