# ubuntu
```
adduser username
deluser -r username
usermod -aG sudo username
```
```
ssh-keygen -t rsa -b 4096
ssh-copy-id username@remotehost
ssh username@remotehost
```
```
apt update
apt upgrade
apt install package1 package2
apt remote package1
apt search package 
```
```
ubuntu-drivers devices
apt install nvidia-driver-XXXX
reboot
nvidia-smi

add-apt-repository ppa:micahflee/ppa
ubuntu-drivers devices
apt install nvidia-driver-XXX
reboot
```
```
apt install screen
screen -S name
(ctrl +a d (detach from screen)
screen -list
screen -r name
```
```
dmidecode -t 1
```
```
apt install ufw
sudo ufw enable 
sudo systemctl status ufw 
sudo ufw allow ssh
sudo ufw status verbose
sudo ufw deny ssh
```
