# SSH SEDANG NETWORK

# Update 
```shell
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```
# Installation
```shell
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/Jagoanneon25/Autoscript/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
# Feature
SSH
CDN CLOUDFLARE
XRAY
V2RAY
SQUID PROXY
TROJAN GFW
AUTO DELETE EXPIRATE ACCOUNT
BACKUP DATA
AUTO REBOOT GMT +5
