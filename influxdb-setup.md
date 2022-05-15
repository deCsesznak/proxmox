# flux2.0
Part of my Crypto Server Project.

I am using proxmox with a Dell r710 server. 

Type:  LXC Container
OS: Debian 

## Step 1 - Download and Start InfluxDB [LINK](https://docs.influxdata.com/influxdb/v2.0/install/?t=Linux)
1.     wget https://dl.influxdata.com/influxdb/releases/influxdb2-2.0.9-amd64.deb
2.     sudo dpkg -i influxdb2-2.0.9-amd64.deb
3.     sudo service influxdb start
4.     sudo service influxdb status
## Step 2 - Install UFW for Firewall
5.     apt install ufw 
6.     ufw enable
7.     ufw allow ssh
8.     ufw allow 8086/tcp

