# Autoscript VPS By Horasss (Admin VPNStores)

1. Update Repositori VPS dan Upgrade agar Tidak Crash Saat Installasi
apt update && apt upgrade -y && update-grub && sleep 2 && reboot

2. Masukkan Perintah Dibawah Untuk Mulai Installasi
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen && wget https://raw.githubusercontent.com/andigoenfx/Autoscript-VPS/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
