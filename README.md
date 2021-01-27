# Rara-chan Bot
Bot written in JavaScript and running on NodeJS and using the popular chatting app

# Features
If you want to know what the features of this bot, you can check in [`BOT COMMAND`](https://github.com/icaksh/rara-bot/blob/main/docs/COMMANDS.MD)

# Getting Started

## System Requirements
1. Node.js v12
2. Minimum 512MB RAM and 2 vCPU (Not tested with 1 vCPU)
3. A number phone

## Additional Information
This bot need WA-API which is private usage, so you can build your own private API and needed to change before using this bot.

# How to Install
## Installing SysReq
### Debian

1. Make sure we don't have dependencies issue 
```
sudo apt -y update && sudo apt -y upgrade
```

2. Because Debian 10 default Node.js version is v10, we need to install Node.js APT Repository
```
sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

3. After that, install Node.js v12
```
sudo apt -y install nodejs
```

4. Believe with God if Node.js has been installed

### Arch Linux

1. Same as Debian, we must make sure we don't have dependencies issue
```
sudo pacman -Syyu
```

2. After that, install Node.js v12
```
sudo pacman -S node
```

### CentOS
Better using Debian bruh, RedHat sucks

## Deploying

Clone this Repository
```
git clone https://github.com/icaksh/rara-bot
```

You can rename the dir with what you want
```
mv rara-bot example-bot
```

Edit what you need to edit (API) in settings.json

Install the dependencies
```
npm install
```

# Usage
1. Start NodeJS
```
npm start
```
2. After that, scan QR code with your app

# Additional Information
## Donate
This bot is 100% free, but if you want to give me a little coffee:
- [`Trakteer`](https://trakteer.id/Icaksh)


## Thanks to
- [WA-Automate](https://github.com/open-wa/wa-automate-nodejs)
- [ArugaZ](https://github.com/ArugaZ/whatsapp-bot)
- [YogaSakti](https://github.com/YogaSakti/imageToSticker)
- [MhankBarBar](https://github.com/MhankBarBar/whatsapp-bot)
- [dandyraka](https://github.com/dandyraka/NoBadWord)

## License
Copyright (c) 2021 Icaksh

The copyright holders grant the freedom to copy, modify, convey, adapt, and/or redistribute this work under the terms of the Massachusetts Institute of Technology License.
A copy of that license is available at [`LICENSE`](https://github.com/icaksh/rara-bot/blob/main/LICENSE)
