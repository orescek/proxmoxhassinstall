# dump commands

in proxmox console:

```
apt update && 
sudo apt dist-upgrade -y 
sudo apt install qemu-guest-agent -y
sudo apt autoremove --purge -y

bash -c "$(wget -qLO - https://github.com/tteck/Proxmox/raw/main/vm/haos-vm-v3.sh)"
```
