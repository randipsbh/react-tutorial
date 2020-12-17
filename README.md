# [react-tutorial](https://reactjs.org/tutorial/tutorial.html)

This [tutorial](https://reactjs.org/tutorial/tutorial.html) doesn’t assume any existing React knowledge.


# Development Environment Setup

## VMware
[Download VMware Fusion (Mac)](https://www.vmware.com/go/getfusion)

[Download VMware Workstation (Windows)](https://www.vmware.com/go/getworkstation-linux)


## Ubuntu
[Download Ubuntu Desktop](https://ubuntu.com/download/desktop)


### Install
[Creating a Linux Virtual Machine Using Fusion (Mac)](https://docs.vmware.com/en/VMware-Fusion/11/com.vmware.fusion.using.doc/GUID-4919245A-CD5D-4FC7-B5D0-4D90DFAFC7F7.html)

[Creating virtual machines in VMware Workstation (Windows)](https://kb.vmware.com/s/article/1018415)


### Update
```sh
sudo apt update && sudo apt dist-upgrade --yes
sudo ubuntu-drivers autoinstall
sudo reboot
```


## Packages
```sh
sudo apt install -y emacs-nox
sudo apt install -y curl git wget
sudo apt install -y gcc g++ make
```


## Google Chrome
```sh
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install -y ./google-chrome-stable_current_amd64.deb
sudo rm ./google-chrome-stable_current_amd64.deb
```


## Visual Studio Code
[Download Visual Studio Code](https://code.visualstudio.com/docs/?dv=linux64_deb)

[Install Visual Studio Code](https://code.visualstudio.com/docs/setup/linux#_debian-and-ubuntu-based-distributions)
```sh
sudo apt install -y ./code*.deb
```


## Node Version Manager
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash


## node.js
```sh
nvm install 14
nvm use 14
```
