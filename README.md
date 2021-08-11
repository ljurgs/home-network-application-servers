Ansible playbook to configure all the application/service servers I currently run on the KVM based hypervisors on my home network. 
Published for educational/reference purposes. 

Applies a number of defaults, configuring:
- UFW
- SSH
- Higher IO throughput for virtio device mapped QCOW2 disk images

Configures the following applications/services on Debian 10 based VMs:
- Samba
- MariaDB
- Plex
- Syncthing

Allows for configuring of and persistent mounting of additional QCOW2 disk images

Example Inventory
-
Comming soon

License
-

BSD-3-Clause
