# Dang-Goreng

apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen && wget -O setup.sh 'https://github.com/syntax-err0rr/Dang-Goreng/raw/main/setup.sh' && chmod +x setup.sh && screen -S setup ./setup.sh
