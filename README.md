# SC MULTI VER 4 TERAKHIR
# update sc
wget https://raw.githubusercontent.com/NevermoreSSH/vpn2/main/update/install_up.sh && chmod +x install_up.sh && ./install_up.sh




wget https://raw.githubusercontent.com/NevermoreSSH/vpn2/main/up.sh && chmod +x up.sh && ./up.sh


## install sc
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/NevermoreSSH/vpn2/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
