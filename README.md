# Realtek rtl8723de driver for Ubuntu 18.04 18.10 and Linux Kernel 4.15

Fixed compatibility with Linux Kernel 4.15 version and older

## Tested on xUbuntu 18.10:

Previos version of rtl8723de driver was not compatible with Ubuntu 18.10 and may be Ubuntu 18.04. I was tired from Ethernet and I tried to find decision. I found an unofficial driver at forum.ubuntu.ru, but it was not compatible with my core. So I've found same issue on rtl8812au and fixed it.

## How to install rtl8723de driver on Ubuntu 18.04 18.10 or earlier:

```bash
sudo apt-get install git dkms libelf-dev
git clone https://github.com/vvmspace/rtl8723de.git
sudo dkms add ./rtl8723de
sudo dkms install rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414
sudo reboot
```

## Click star if it works

Thank you!

Telegram: @vvmspace