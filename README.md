#### bbr
wget -N --no-check-certificate "https://github.000060000.xyz/tcp.sh" && chmod 777 tcp.sh && ./tcp.sh

wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/tcp.sh && chmod 777 tcp.sh && ./tcp.sh
#### ddns/brook
yum install -y iptables && yum install bind-utils -y

apt-get install iptables && apt-get install dnsutils

wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/brook-pf-mod.sh && chmod 777 brook-pf-mod.sh && bash brook-pf-mod.sh
#### caddy
wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/caddy.sh && chmod 777 caddy.sh && bash caddy.sh install http.filemanager
#### net_speeder
wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/nsp.sh && chmod 777 nsp.sh && bash nsp.sh
#### trojan
source <(curl -sL https://git.io/trojan-install)

source <(curl -sL https://git.io/trojan-install) --remove

wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojan_panel_web/master/trojan-web-panel.sh" && chmod 777 trojan-web-panel.sh && ./trojan-web-panel.sh
#### superbench
wget https://raw.githubusercontent.com/msoayu56/speedtest/master/superbench.sh && chmod 777 superbench.sh && bash superbench.sh
#### wireguard
apt update -y && apt upgrade -y

reboot

apt install linux-headers-$(uname -r) -y

wget https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/debian.sh && chmod 777 debian.sh && bash debian.sh
##### 开机配置
yum update -y

apt update -y && apt-get update -y

yum install unzip -y && yum install gcc -y

apt install unzip -y && apt install gcc -y

chmod 777 /etc/resolv.conf && echo -e "nameserver 223.5.5.5
nameserver 223.6.6.6" > /etc/resolv.conf

chmod 777 /etc/hosts && echo "151.101.108.133 raw.githubusercontent.com" >> /etc/hosts

chmod 777 /etc/hosts && echo "13.229.188.59 github.com" >> /etc/hosts


CentOS 7.0默认使用的是firewall作为防火墙

查看防火墙状态

firewall-cmd --state

停止firewall

systemctl stop firewalld.service

禁止firewall开机启动

systemctl disable firewalld.service

开启防火墙

systemctl start firewalld.service

设置开机自启

systemctl enable firewalld.service

重启防火墙

systemctl restart firewalld.service
