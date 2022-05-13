# Proxmox
Repository to manage Proxmox setup

# Objective
My objective in building this repository to consolidate all the different sources / instructions I used to standup proxmox. 

# Hardware
- Server:  DELL r710 (on-premise)
- RAM: 144GB
- CPU:  XEON x 2
- Cores:  16<br>


# Instructions to Setup
1. Verify the server is at the latest BIOS, iDRAC, RAID <br>
[ISO that worked for me](https://www.dropbox.com/s/ujw0sczpz1zk79k/DELL-R710.iso.iso?dl=0)<br>
[Reddit Post with ISO Link](https://www.reddit.com/r/homelab/comments/gixkba/dell_r710_firmware_updates_these_days/)
2. Download the Proxmox ISO image from [LINK](https://www.proxmox.com/en/proxmox-ve/get-started)
3. Use [Rufus](https://rufus.ie/en/) to flash the downloaded ISO to USB
4. Boot the server from the USB drive
5. Follow the Proxmox installation instructions
6. Navigate the the Proxmox URL specified

