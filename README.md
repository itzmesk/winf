# kj


<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">

  </a>
</p>
<p align="center">
  <a href="hhttps://github.com/itzmesk/winf/stargazers">
    <img src="https://img.shields.io/github/stars/itzmesk/winf/?style=social">

  </a>
  
  <a href="https://github.com/itzmesk/winf/fork">
    <img src="https://img.shields.io/github/forks/itzmesk/winf?label=Fork&style=social">

  </a>  
</p>




## How to use the bot
* Add bot to your group with admin rights.

* Add bot to all channels which you want to link with all admin rights!

## Bot Commands - Works in Group only

(You need to be a Auth User in order to use these commands)

* /add channelid  -  Links channel to your group.
or
* /add @channelusername - Links channel to your group.

<i>NOTE : You can get your channel ID from @ChannelidHEXbot </i>


* /del channelid  -  Delinks channel from group
or
* /del @channelusername  -  Delinks channel from group

<i>NOTE : You can get connected channel details by /filterstats </i>


* /delall  -  Removes all connected channels and filters from group!

* /filterstats  -  Check connected channels and number of filters.

## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)]

### Deploy in your vps
```sh
git clone https://github.com/itzmesk/winf
cd winf
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
```

## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* APP_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* TG_USER_SESSION  - A pyrogram user session string. Generate by [clicking here](https://repl.it/@prgofficial/String-Gen)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [MissRose Bot](https://telegram.dog/MissRose_bot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* DOC_SEARCH  - Should bot search for document files ( Give 'yes' or 'no' )

* VID_SEARCH  - Should bot search for video files ( Give 'yes' or 'no' )

* MUSIC_SEARCH  - Should bot search for music files ( Give 'yes' or 'no' )

