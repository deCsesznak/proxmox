# grafana
Part of my Crypto Server Project.

I am using proxmox with a Dell r710 server. 

Name: grafana
Type: LXC Container
OS: Debian 

## Step 1 - Update
1.     apt update
2.     apt upgrade
## Step 2 - Download and Start Grafana 
1.     apt-get install -y gnupg2 curl software-properties-common
2.     curl https://packages.grafana.com/gpg.key |  apt-key add -
3.     add-apt-repository "deb https://packages.grafana.com/oss/deb stable main"
4.     sudo apt-get update
5.     sudo apt-get -y install grafana
6.     sudo systemctl enable --now grafana-server
7.     systemctl status grafana-server.service
8.     apt install ufw 
9.     ufw enable
10.     ufw allow ssh
11.     ufw allow 3000/tcp