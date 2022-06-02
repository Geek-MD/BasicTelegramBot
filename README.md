<h1 align="center">
BasicTelegramBot
</h1>
<p align="center">A Telegram Bot you can use as a basis for your bot development.</p>
<p />
<p align="center"><a href="https://www.python.org/"><img alt ="Made with Python" src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg"> <a href="https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt"><img alt="MIT License" src="https://img.shields.io/github/license/Naereen/StrapDown.js.svg"></a> <a href="https://GitHub.com/Geek-MD/BasicTelegramBot/releases/"><img alt="GitHub Releases" src="https://img.shields.io/github/release/Geek-MD/BasicTelegramBot.svg"> <a href="https://github.com/Geek-MD/BasicTelegramBot/"><img alt="GitHub Branches" src="https://badgen.net/github/branches/Geek-MD/BasicTelegramBot"></a> <img alt="GitHub Stars" src="https://badgen.net/github/stars/Geek-MD/BasicTelegramBot"></p>
<p />

## Basic Installation
This bot is designed to work on a ***Raspberry Py*** and relies mainly on *[python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)*, so you have to install this package first with
  
```
pip install python-telegram-bot
```

Also you have to install *gpiozero*, *psutil* and *requests* libraries used for */system* and */version* command.

```
pip install gpiozero
pip install psutil
pip install requests
```

Now clone this repo with
  
```
git clone https://github.com/Geek-MD/BasicTelegramBot.git
```
  
Edit ***config.json*** and add your bot Telegram token, id number of allowed and admin users, id number of bot owner, chat id used by your bot, bot id and you're done. Now run with

```
python basictelegrambot.py
```
  
If you want to run the bot at startup, or advanced configuration, check the [Wiki](https://github.com/Geek-MD/SmartHomeBot/wiki).
