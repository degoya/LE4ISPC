# LE4ISPC (Single or Multi Server Setup)
Let's Encrypt With Auto Updater is for ISPConfig 3 (Single or Multi Server Setup) and other services like Postfix+Dovecot, Pure-ftpd, Monit etc. It will automatically create Let's Encrypt for any ISPConfig server hostname FQDN if none exists; and secure its control panel and other services; if they are available and installed.

# LATEST HOW-TO
In your terminal, in root mode, simply run this after you have installed any of your ISPConfig server build:
```
cd /etc/ssl
wget https://raw.githubusercontent.com/ahrasis/LE4ISPC/master/le4ispc.sh --no-check-certificate
chmod +x le4ispc.sh
./le4ispc.sh
```

# OLDER HOW-TO'S
https://github.com/ahrasis/LE4ISPC/tree/master/nginx

https://github.com/ahrasis/LE4ISPC/tree/master/apache

# LICENSE
BSD3
