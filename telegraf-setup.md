# grafana
Part of my Crypto Server Project.

I am using proxmox with a Dell r710 server. 

Name: telegraf
Type: LXC Container
OS: Debian 

## Step 1 - Update
1.     apt update
2.     apt upgrade
## Step 2 - Download and Start Telegraf
1.     wget https://dl.influxdata.com/telegraf/releases/telegraf_1.22.3-1_amd64.deb
2.     sudo dpkg -i telegraf_1.22.3-1_amd64.deb
3.     telegraf config > telegraf.conf
4.     apt-get install ipmitool