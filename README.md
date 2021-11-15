# htpc_server_guide
- Install docker
-- 

- Install docker compose


# NFS
```
## Install NFS tools
sudo apt update
sudo apt install -y nfs-common

## Create mount Directory
sudo mkdir /var/movies

##  Update /etc/fstab with the following
### 192.168.1.100:/volume1/movies /var/movies  nfs      defaults,vers=4    0       0
sudo nano /etc/fstab
```


