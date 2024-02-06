# Virtualbox
## Config Network Connectivity and Sharing Between a VirtualBox Host and Guest Virtual Machine
### 1. Check IP
  a. Guest Virtual Machine: ip a or ipp addr show
  b. VirtualBox Host: ipconfig > look for host only network (e.g. 192.168.56.1)
  c. Or go to control panel > network and internet > advanced network settings
  d. Check VM name: settings > about
### 2. Config VirtualBox VM
  a. Settings > Network > Adapter 2
  b. Host-only Adapter > Advanced (default)
  c. Config firewall if neccessary
  
