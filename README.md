# VPN
PPTP IKEV2 and SHADOWSOCKS  with centos 6.x

安装方式：
yum install -y git

git clone https://github.com/charlesbao/VPN.git

cd VPN

chmod 777 shadowsocks.sh
./shadowsocks.sh



sh installVPN.sh 2>&1 | tee installVPN.log
