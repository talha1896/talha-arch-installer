## Our Message
Put an end to the unjust killing of innocent Muslims in Palestine,Kashmir by Israel,India and ensure that both are granted their rightful rights.
# talha-arch-installer

A simple script to install Arch linux easily.


## Reason of creating this script

Although now Arch linux has own installer script but i don't know it dost not work for me,so i created my own.Thats why it a personel installer,instead of universal.That install arch with my taste.Feel free to customize as you want.Thanks!

## Features
- minimal
- option for intel or amd
- option for Bios or uefi systems

## Connect to a network for wireless
To get an interactive prompt do:
$ iwctl
# First, if you do not know your wireless device name, list all Wi-Fi devices: 
$ device list
# then
$ station device scan
# You can then list all available networks: 
$ station device get-networks
# Finally, to connect to a network: 
$ station device connect SSID

## Installation

Install by running 

```bash
  git clone https://github.com/talha1896/talha-arch-installer.git
  cd talha-arch-installer
  ./talha-arch-installer
```


## FAQS

#### What is the default kernal and partition layout?

kernal is default Linux and partition layout is ext4.

#### Which pc supported?

You can use this script in Bios or uefi system,with intel or amd drivers.
