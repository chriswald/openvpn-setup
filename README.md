# OpenVPN Setup

This project just contains notes on setting up and managing OpenVPN, including adding new clients

## Download openvpn-install.sh
GitHub repository: https://github.com/Nyr/openvpn-install

    wget https://git.io/vpn -O openvpn-install.sh

## Running openvpn-install.sh
    sudo chmod +x openvpn-install.sh
    sudo bash openvpn-install.sh

## Start/stop/restart OpenVPN
    sudo systemctl start openvpn-server@server.service
    sudo systemctl stop openvpn-server@server.service
    sudo systemctl restart openvpn-server@server.service

## Add a new client
    sudo bash openvpn-install.sh

## Edit settings
    sudo vim /etc/openvpn/server/server.conf
