# shanghai
wget -N --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/tcp.sh && chmod 777 tcp.sh && ./tcp.sh

wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/brook.sh && chmod 777 brook.sh && ./brook.sh

wget --no-check-certificate https://raw.githubusercontent.com/BrunuhVille/shanghai-down-cn/master/caddy.sh && chmod 777 caddy.sh && bash caddy.sh install http.filemanager

chmod 777 /etc/resolv.conf && echo -e "nameserver 223.5.5.5
nameserver 223.6.6.6" > /etc/resolv.conf
