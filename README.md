
<p align="center">
<img src="https://github.com/LingziKul/SHIKIMORIbot-MdV1/blob/v7.1/image/lol_1.jpg" alt="SHIKIMORI BOT" width="100"/>


</p>
<p align="center">
<a href="#"><img title="SHIKIMORIBOT MULTI DEVICE" src="https://img.shields.io/badge/SHIKIMORIBOT MULTI DEVICE-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/DikaArdnt"><img title="Author" src="https://img.shields.io/badge/Author-Dika-red.svg?style=for-the-badge&logo=github"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1"><img title="Recode" src="https://img.shields.io/badge/Recode-ZeeoneOfc-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/zeeone-ofc/followers"><img title="Followers" src="https://img.shields.io/github/followers/zeeone-ofc?color=red&style=flat-square"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/LingziKul/SHIKIMORIbot-MdV1?color=blue&style=flat-square"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1/network/members"><img title="Forks" src="https://img.shields.io/github/forks/LingziKul/SHIKIMORIbot-MdV1?color=red&style=flat-square"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/LingziKul/SHIKIMORIbot-MdV1?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1"><img title="Open Source" src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103"></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1/"><img title="Size" src="https://img.shields.io/github/repo-size/LingziKul/SHIKIMORIbot-MdV1?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fzeeone-ofc%2FSHIKIMORIbot-Md&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1#requirements">Requirements</a> •
  <a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1#instalasi">Installation</a> •
  <a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1#thanks-to">Thanks to</a> •
  <a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1#Official-Group"> Official Group Bot</a> •
  <a href="https://github.com/LingziKul/SHIKIMORIbot-MdV1#donate">Donate</a>
</p>
</div>


---

## Information
> Alpahbot-Md adalah bot yang memakai base dari [Hisoka-Morou](https://github.com/DikaArdnt/Hisoka-Morou). SHIKIMORIbot-Md is a bot whatsapp using a Baileys library.

## Support Language

- [x] Indonesia
- [x] Spanish
- [x] English

But some I haven't changed the language 🛐

# Instalasi
## Heroku Buildpack
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## How to Get Mongodb URI
- Tonton [Di YouTube](https://youtu.be/M8H9S3djxTg)
<img src="https://telegra.ph/file/682c1315ff9a43bb1a724.jpg" width="300">
- Jika sudah memiliki database mongoDB ikuti tutorial di bawah

## HOW TO CONNECT TO MONGODB

- Salin Url database mongoDB
- Constoh `worker: node . --db 'Link Database MongoDb'`
- Contoh `worker: node . --db 'mongodb+srv://mongodb-bot:abcdefghij@zeeoneofc.aWpl9.mongodb.net/?retryWrites=true&w=majority'`

## For Termux
```ts
apt update && apt upgrade
pkg install bash
git clone https://github.com/LingziKul/SHIKIMORIbot-MdV1.git
cd SHIKIMORIbot-Md
bash install.sh
```

## Edit file
`./settings.js`
```ts
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = false //status online (online)

// Other
global.botname = "SHIKIMORIbot-Mdོ"
global.ownername= "ᴹᴿ᭄ ZeeoneOfcོ ×፝֟͜×"
global.myweb ="https://api-SHIKIMORIbot.herokuapp.com/"
global.youtube = "https://youtube.com/c/ZeeoneOfc"
global.github = "https://zeeone-ofc.github.io/"
global.email = "zeeoneofc@gmail.com"
global.region = "Indonesia"
global.ownernomer = "62887435047326"
global.ownernomerr = "+62887435047326"
global.thumbnail = "./image/lol.jpg"
global.donasi = "./image/donasi.jpg"
global.background_welcome="https://telegra.ph/file/90a931648de597820bc08.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["62887435047326","62887435047326","6285342106390"] //ganti agar fitur owner bisa di gunakan
global.packname = '© SHIKIMORIbot-Mdོ' //sticker wm
global.author = 'Di Buat Oleh ZeeoneOfc' //sticker wm
global.sessionName = 'session'
```

## ```HOW TO DEPLOY```

[`Click Here For Tutorial`](https://youtu.be/SdKHkld2NcI)<br>

----------

<p align="center">
  <a href="https://youtu.be/SdKHkld2NcI"><img src="https://a.top4top.io/p_2081imvxm1.jpg" />
</p>

## Donate
- [Saweria](https://saweria.co/zeeoneofc)
- [Dana](https://j.top4top.io/p_20532posd1.jpg)
- [Ovo](https://h.top4top.io/p_2053vk0uw1.jpg)
- [Gopay](https://i.top4top.io/p_2053em3vh1.jpg)

# Official Group
- [Group 1](https://chat.whatsapp.com/EU890BcXjyBDkNaUT5WmYV)
- [Group 2](https://chat.whatsapp.com/E8NExJwIbhBJYzssfqJNsE)
- [Group 3](https://chat.whatsapp.com/KCSqHTky1apG7ApePsfiPy)
- [Group 4](https://chat.whatsapp.com/KwmvHr7VMFj7r5ry9xmMsU)
- [Group 5](https://chat.whatsapp.com/ELa7GhU0sP4EvXcVimQYtz)

# Thanks to
<a href="https://github.com/DikaArdnt"><img src="https://github.com/DikaArdnt.png?size=100" width="100" height="100"></a> | [![NURUTOMO](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) 
---|---
[Dika](https://github.com/DikaArdnt)  | [Nurutomo](https://github.com/Nurutomo)
Owner Hisoka-Morou | Constributor |
<a href="https://github.com/MhankBarBar"><img src="https://github.com/MhankBarBar.png?size=100" width="100" height="100"></a> | [![FATIH](https://github.com/fatiharridho.png?size=100)](https://github.com/fatiharridho) 
[Mhankbarbar](https://github.com/MhankBarBar)  | [Fatih A.](https://github.com/fatiharridho)
Constributor | For Help |
<a href="https://github.com/FERDIZ-afk"><img src="https://github.com/FERDIZ-afk.png?size=100" width="100" height="100"></a> | [![RASHID](http://github.com/rashidsiregar28.png?size=100)](http://github.com/rashidsiregar28) 
[Ferdiz](https://github.com/FERDIZ-afk)  | [Rashid](https://github.com/rashidsiregar28)
For Help | Owner Chikabot |
<a href="https://github.com/adiwajshing"><img src="https://github.com/adiwajshing.png?size=100" width="100" height="100"></a> | [![ZEEONE](http://github.com/zeeone-ofc.png?size=100)](http://github.com/zeeone-ofc) 
[Adiwajshing](https://github.com/adiwajshing) | [zeeone-ofc](https://zeeone-ofc.github.io)
Owner of Baileys | Owner of Api SHIKIMORIbot |

