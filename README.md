
# Need
<br>
- DOMAIN (MUST)<br>
- DEBIAN 9/10<br>
- Ubuntu 18/20 LTS<br>
- CPU MIN 1 CORE<br>
- RAM 1GB<br>
<br>

# Setting Cloudflare
<br>
- SSL/TLS : FULL<br>
- SSL/TLS Recommender : OFF<br>
- GRPC : ON<br>
- WEBSOCKET : ON<br>
- Always Use HTTPS : OFF<br>
- UNDER ATTACK MODE : OFF<br>
<br>

# Pointing
![Pointing](https://raw.githubusercontent.com/givpn/AutoScriptXray/master/image/pointing.png)

### Fitur Script
• SSH & OpenVPN

• SSH Websocket TLS & No TLS

• OHP SSH & OHP Dropbear & OHP OpenVPN

• XRAY VMESS 

• XRAY VLESS

• XRAY TROJAN

• SHADOWSOCKS

• SSR

• PPTP VPN

• L2TP VPN

• SSTP VPN

• WIREGUARD

• TROJAN GO

• Backup Data ALL Service

• Restore Data ALL Service

# Service & Port

• OpenSSH                 : 443, 22

• OpenVPN                 : TCP 1194, UDP 2200, SSL 990

• Stunnel5                : 443, 445, 777

• Dropbear                : 443, 109, 143

• Squid Proxy             : 3128, 8080

• Badvpn                  : 7100, 7200, 7300

• Nginx                   : 89

• Wireguard               : 7070

• L2TP/IPSEC VPN          : 1701

• PPTP VPN                : 1732

• SSTP VPN                : 444

• Shadowsocks-R           : 1443-1543

• SS-OBFS TLS             : 2443-2543

• SS-OBFS HTTP            : 3443-3543

• XRAYS Vmess TLS         : 8443

• XRAYS Vmess None TLS    : 80

• XRAYS Vless TLS         : 8443

• XRAYS Vless None TLS    : 80

• XRAYS Trojan            : 2083

• Websocket TLS           : 443

• Websocket None TLS      : 8880

• Websocket Ovpn          : 2086

• OHP SSH                 : 8181

• OHP Dropbear            : 8282

• OHP OpenVPN             : 8383

• Trojan Go               : 2087

 ### Server Information & Other Features

• Timezone                : Asia/Jakarta (GMT +7)

• Fail2Ban                : [ON]

• Dflate                  : [ON]

• IPtables                : [ON]

• Auto-Reboot             : [ON]

• IPv6                    : [OFF]

• Autoreboot On 05.00 GMT +7

• Futo Delete Expired Account

• Full Orders For Various Services

• White Label

# install
- Step 1 Update
```
apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y && reboot
```
- Step 2 Install
```
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/PechScript/PechVPN-Manager/PechVPN/setup.sh && chmod +x setup.sh && ./setup.sh
```

<p align="center">
<a href="https://opensource.org/licenses/MIT"> <img src="https://img.shields.io/badge/License-MIT-yellow.svg" style="max-width:200%;">
