#!/bin/bash

echo -e "\033[1;31mATENCAO!!\033[0m"
echo " "
echo -e "\033[1;33mEssas script ira liberar as portas 80 8080 1194 81 443 442 servidor
\033[0m"
echo""
sudo apt install firewalld &&
sudo firewall-cmd --zone=public --permanent --add-port=80/tcp &&
sudo firewall-cmd --zone=public --permanent --add-port=8080/tcp &&
sudo firewall-cmd --zone=public --permanent --add-port=1194/tcp &&
sudo firewall-cmd --zone=public --permanent --add-port=443/tcp &&
sudo firewall-cmd --zone=public --permanent --add-port=81/tcp &&
sudo firewall-cmd --zone=public --permanent --add-port=442/tcp &&
sudo firewall-cmd --reload &&
sudo firewall-cmd --zone=public --list-ports
