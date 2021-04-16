## ⚛️ Deploying on Heroku
--> https://github.com/MsGsuite/CloneBot_Heroku
<br/><br/>

## 💠 Host the bot on your computer

1. Download the repo : https://github.com/MsGsuite/CloneBot/archive/refs/heads/master.zip
2. Open the config.ini file (inside the telegram_gcloner folder) and fill the following values :


> path_to_gclone =./gclone  ⚠ Don't touch this
>
> telegram_token = go to @BotFather and send /newbot to get one
>
> user_ids = -1 = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)
> 
> group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
> 
> gclone_para_override = leave this empty if you don't know how to use it

3. Install [python](https://www.python.org/downloads/)
4. open CMD and cd to the folder containing the bot
5. run `pip install -r requirements.txt`
6. cd to the telegram_gcloner folder and run : `py telegram_gcloner.py`
7. Start your bot and you can copy your data !
<br/><br/>

## 📢 Follow us:
- Team drive generator : https://td.msgsuite.workers.dev/
- Telegram channel : https://t.me/MsGsuite
- Telegram chat : https://t.me/MsGsuiteChat

## ❤️ Credits & thanks :
- [wrenfairbank](https://github.com/wrenfairbank/telegram_gcloner) for the original python script
- [smartass08](https://github.com/smartass08/telegram_gcloner) to adapt the scrip to heroku
- [anymeofu](https://github.com/anymeofu/CloneBot) for making the Direct Heroku deployable Version
- Zero-The-Kamisama to making me discover this amazing bot and the detailed instructions
