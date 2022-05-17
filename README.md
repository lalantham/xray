# Xray-Script

### Disclaimer: This is for my use only. I have no rights and the total rights belong to the developer.

Source URL: [Click Here](https://github.com/iamtrazy/bash-xray-script).

#### Install Command for Oracle Servers
```console
sudo iptables -I INPUT 6 -m state --state NEW -p tcp --dport 443 -j ACCEPT && sudo netfilter-persistent save && sudo apt-get update -y && sudo apt-get upgrade -y && sudo git clone https://github.com/iamtrazy/bash-xray-script && cd bash-xray-script && sudo chmod +x xray-nodomain.sh && sudo ./xray-nodomain.sh
```

#### Install Command for Other Cloud Servers
```console
sudo apt-get update -y && sudo apt-get upgrade -y && sudo git clone https://github.com/iamtrazy/bash-xray-script && cd bash-xray-script && sudo chmod +x xray-nodomain.sh && sudo ./xray-nodomain.sh
```

#### Get UUID v4
[UUID Generator](https://www.uuidgenerator.net/version4).
