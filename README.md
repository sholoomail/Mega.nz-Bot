# Mega.nz-Bot
A Simple Telegram Bot written in Python using Pyrogram Library to Do [Somethings](https://github.com/Itz-fork/Mega.nz-Bot#features) Related to [Mega.nz](https://mega.nz/) Cloud Storage.

# Features
- All Mega.nz File Links supported
- No login required
- Auto Detect File Type Before Upload to Telegram
- Can be used as Private or Public Bot
- Mega User Account Supported
- Upload Files From Telegram to Mega.nz
- Import Files From Public Mega.nz Url

# Deploy
Deploy your own Bot ♥️! **Star 🌟 Fork 🍴 and Deploy**

### Config Vars 📓,

**Mandatory Vars,**
- `APP_ID` - Your APP_ID. Get it from [my.telegram.org](my.telegram.org)
- `API_HASH` - Your API_ID. Get it from [my.telegram.org](my.telegram.org)
- `AUTH_USERS` - Telegram IDs Of Auth Users, Only they can use this bot (If you didn't set this as public bot). Separate them by a space. (Ex: `123445 2648589`)
- `BOT_TOKEN` - Your Bot Token From [@BotFather](https://t.me/BotFather)

**Non Mandatory Vars,**
- `IS_PUBLIC_BOT` - Set this to 'True' if you want to set Download Function as Public. Default to 'False'
- `MEGA_EMAIL` - Fill this if you want to use your own Mega Account. This is your Mega account Email
- `MEGA_PASSWORD` - Fill this if you want to use your own Mega Account. This is your Mega account Password
- `USER_ACCOUNT` Set this to 'True' If you want to use your own Mega Account. Default to 'False'

### With Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sholoomail/Mega.nz-Bot)

### With VPS/PC

- Clone the Repo,
```
git clone https://github.com/Itz-fork/Mega.nz-Bot
```
- Enter the directory,
```
cd Mega.nz-Bot
```
- Install Requirements,
```
pip3 install -r requirements.txt
```
- Fill Config Vars, </br>
For PCs - Use Normal Text Editor to Fill Config Vars </br>
For Vps - If you haven't installed nano yet, Read This - [How to install Nano in your computer/Vps](https://gist.github.com/Itz-fork/fd11c08ef7464bdae3663a1f9c77c9e9)

Fill Config vars with your own values. If you don't know  how to get them, Read This - [How to Get Config Values](https://github.com/Itz-fork/Mega.nz-Bot#features)
```
sudo nano config.py
```
- Run the Bot,
```
python3 main.py
```

# Support
<a href="https://t.me/Nexa_bots"><img src="https://img.shields.io/badge/Support_Group-0a0a0a?style=for-the-badge&logo=telegram&logoColor=white"></a>
