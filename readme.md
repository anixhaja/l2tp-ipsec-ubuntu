### L2TP over IPsec VPN on Ubuntu

```

export VPN_SERVER_IP="Server ip"
export VPN_IPSEC_PSK="Shared key"
export VPN_USER="User"
export VPN_PASSWORD="Password"

sudo su
sh init
sh start

sh disconnect # close the connection

```