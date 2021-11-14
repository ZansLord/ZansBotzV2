
<div align="center">
<img src="https://i.ibb.co/QQDXr17/20211031-234304-1-3.jpg" alt="ZansBotz" width="500" />

# **ZansBotzV2**

> ZansBotz is a multipurpose WhatsApp bot using adiwajshing/baileys library!
>ZansBotz Is Recode Base XinzBotz
>

<h3 align="center">Made with ❤️ by</h3>
<p align="center">
  <a href="https://github.com/ZansLord"><img src="https://i.ibb.co/XyChcGQ/20211102-192101.jpg" height="128" width="128" /></a>
  <a href="https://github.com/adiwajshing"><img src="https://i.ibb.co/LhCtVR1/20211108-163050.jpg" height="128" width="128" /></a>
  <a href="https://github.com/naylachan"><img src="https://i.ibb.co/T2gyJhn/20211014-163216-transcpr.jpg" height="128" width="128" /></a>
</p>

<p align="center">
  <a href="https://github.com/ZansLord"><img title="Author" src="https://img.shields.io/badge/Author-ZansLord-purple.svg?style=for-the-badge&logo=github" /></a>
</p>

<p align="center">
  <a href="https://github.com/ZansLord/ZansBotzV2"><img title="Stars" src="https://img.shields.io/github/stars/Zanslord/ZansBotzV2?color=red&style=flat-square" /></a>
  <a href="https://github.com/ZansLord/ZansBotzV2/network/members"><img title="Forks" src="https://img.shields.io/github/forks/ZansLord/ZansBotzV2?color=red&style=flat-square" /></a>
  <a href="https://github.com/ZansLord/ZansBotzV2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/ZansLord/ZansBotzV2?label=watchers&color=blue&style=flat-square" /></a> <br>
  <a href="https://www.npmjs.com/package/@open-wa/wa-automate"><img src="https://img.shields.io/npm/v/@open-wa/wa-automate.svg?color=green" /></a>
  <img src="https://img.shields.io/node/v/@open-wa/wa-automate" />
  <img">Installation</a> •
  <a href="https://github.com/ZansLord/ZansBotzV2#thanks-to">Thanks to</a> •


<h4 align="center">
  <a href="https://chat.whatsapp.com/LTL9J5K0dxp65WspruIQuW">Join WA BTMCI!</a>
</h4>
</div>

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://www.gyan.dev/ffmpeg/builds/)
* [Tesseract](https://s.id/vftesseract)
* Any text editor

# Installation
## 📝 Cloning this repo
```cmd
> git clone https://github.com/ZansLord/ZansBotzV2.git
> cd ZansBotzV2
```

## ✍️ Editing the file
Edit the required value in `config.json`.
```json
{
  "ownerNumber": [ "62852*********@s.whatsapp.net" ],
  "limitCount": 20,
  "gamewaktu": 60,
  "botName": "ZansBot",
  "pathImg": "./media/yo.jpg",
  "lolkey": "APIKEY",
  "zekskey": "chika-key",
  "tobzkey": "Tobzzz17",
  "aqulzkey": "APIKEY",
  "sesidInsta": "1548633294%3AqTFgHr7mE6tmU8%3A13",
  "sessionName": "zans",
  "gcount": {
    "prem": 999999,
    "user": 25
  },
  "packSticker": "By ZansBotz",
  "authorSticker": "BTMCIIND"
}

   
```

`ownerBot`: your WhatsApp number.  
`prefix`: based on the latest update, you don't need to change the prefix, because this bot has multiple prefix.  
`lol`: LolHuman API key. You can get it [here](https://lolhuman.herokuapp.com/) by creating an account.  
`authorStick`: name of the author sticker pack.  
`packStick`: name of the sticker pack.  


## 🧾 Installing the Tesseract
* Download the file [here](https://s.id/vftesseract).
* After that, run downloaded file as Administrator.
* Complete the installation.
* Run Command Prompt as Administrator.
* Run this command:
```cmd
> setx /m PATH "C:\Program Files\Tesseract-OCR;%PATH%"
```
It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've Tesseract installed, verify that it's working by running this command to see version number:
```cmd
> tesseract -version
```

## 🛠️ Installing the FFmpeg
* Download one of the available versions of FFmpeg by clicking [this link](https://www.gyan.dev/ffmpeg/builds/).
* Extract the file to `C:\` path.
* Rename the extracted folder to `ffmpeg`.
* Run Command Prompt as Administrator.
* Run this command:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've FFmpeg installed, verify that it's working by running this command to see version number:
```cmd
> ffmpeg -version
```

## 🔍 Installing the dependencies
```cmd
> npm install
```

## 🆗 Running the bot
Regular node:
```cmd
> npm start
```

PM2:
```cmd
> pm2 start main.js
> pm2 monit
```

PM2 WITH ATTACH:
```cm d
> pm2 start main.js --attach
```

PM2 with cron job (restart after 5 hours):
```cmd
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp in your phone!

# Thanks to
* [`adiwajshing/baileys`](https://github.com/adiwajshing/baileys)
* [`YogaSakti/imageToSticker`](https://github.com/YogaSakti/imageToSticker)
* [`uukina`](https://github.com/uukina)
* [`MrPawNO`](https://github.com/MrPawNO)
* [`Pahri123`](https://github.com/Pahri123)
* [`LeviathanH`](https://github.com/LeviathanH)
* [`ferlitopym`](https://github.com/ferlitopym)
* [`AlvioAdjiJanuar`](https://github.com/AlvioAdjiJanuar)
* [`VideFrelan`](https://github.com/VideFrelan)
* [`VirusLauncher`](https://github.com/VirusLauncher)
* [`shansekai`](https://github.com/shansekai)
* [`Baguettou`](https://github.com/Baguettou)
* [`HAFizh-15`](https://github.com/HAFizh-15)
* [`TheSploit`](https://github.com/TheSploit)
* [`rashidsiregar28`](https://github.com/rashidsiregar28)
* [`irham01`](https://github.com/irham01)
* [`hardiantojek93`](https://github.com/hardiantojek93)
* [`gamingrkp`](https://github.com/gamingrkp)
* [`Hexagonz`](https://github.com/hexagonz)
* [`DITTAZ`](https://youtu.be/TXzHMehgQJM)
