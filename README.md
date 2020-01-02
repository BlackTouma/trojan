# DO NOT FORK OR STAR!

# 环境安装 （注意root环境下运行）
> apt-get update -y

> apt-get install build-essential devscripts debhelper cmake libboost-system-dev libboost-program-options-dev libssl-dev default-libmysqlclient-dev python3 curl openssl -y
---
# 安装命令：
curl -O https://raw.githubusercontent.com/BlackTouma/trojan/master/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh
---
# 基本命令：
> systemctl start trojan                开始

> systemctl stop trojan                 停止

> systemctl restart trojan              重启

> systemctl status trojan               状态

---
支持的系统：
- ubuntu 16.04+
- debian 9(理论上应该支持debian 8)
- centos 7+
- RHEL 7+
