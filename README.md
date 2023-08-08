
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
# install
- Step 1 Update
```
apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y && reboot
```
- Step 2 Install
```
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/PechScript/AutoRunServer/PechVPN/setup.sh && chmod +x setup.sh && ./setup.sh
```

<p align="center">
<a href="https://opensource.org/licenses/MIT"> <img src="https://img.shields.io/badge/License-MIT-yellow.svg" style="max-width:200%;">
