# vpn

# INSTAL VPN SERVER PREMIUM PRIBADI DI VPS
	==============================================
BAGIAN 1
INSTALL WGET
 ```
apt install wget
 ```
JALANKAN SCRIPT
 ```
wget https://github.com/bpbd1/vpn/blob/main/vpnsetup.sh
 ```
BAGIAN 2
EDIT USERNAME & PASWORD
 ```
nano -w vpnsetup.sh
 ```
BAGIAN 3
JALANKAN SCRIPT
 ```
sudo sh vpnsetup.sh
 ```
BAGIAN 4
MELIHAT & TAMBAH USER
 ```
cd /etc/ppp && nano chap-secrets
 ```
BAGIAN 5
KONFIGURASI IP ADDRES RANGE REMOT (OPTIONAL)
 ```
nano /etc/xl2tpd/xl2tpd.conf
 ```
BAGIAN 6
RESTART SERVICE
 ```
/etc/init.d/xl2tpd stop
/etc/init.d/xl2tpd restart
 ```
COBA KONEKSIKAN DI PC, MIKROTIK, HANDPHONE Dsb.
===============================================
