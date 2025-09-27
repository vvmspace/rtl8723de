# Realtek rtl8723de driver for Ubuntu 18.04 18.10 and Linux Kernel 4.15

Fixed compatibility with Linux Kernel 4.15 version and older

## PROJECT CLOSED

Look: https://github.com/smlinux/rtl8723de

Thank you!

BTC: 15f2m6wXdGnQ6TN9Co23uxnmjXfJNFXXCs

## Ubuntu 20.04:

Driver is in the box. Don't know which.

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

## Check also

- [AI setup](https://aisetup.me) - explain your project, answer questions for details and get cursor rules and instructions capatible with the most vibe coding editors like Cursor, WindSurf, Codex etc.
- [Paste to QR code](https://paste2qr.com) - QR code generator with multiple languages support.
- [XMR to USDT exchange](https://xmr2usdt.com) & [USDT to XMR exchange](https://usdt2xmr.com) - XMR <> USDT exchange with guides and news about Monero.
- [Potatoes recipes](https://potatoes.recipes) - potato recipies, history of potato and news.

## Click star if it works

Thank you!

Telegram: @vvmspace
