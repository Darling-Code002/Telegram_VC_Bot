# Siesta Music Bot

Telegram Voice-Chat Bot To Play Music With Pytgcalls From Various Sources In Your Group.




## Requirements

### Account requirements
- A Telegram account to use as the music bot, **You cannot use regular bot accounts, as they cannot join voice chats. *It must be a user account.***
- API_ID and API_HASH for that account.
- The account must be an admin of the chat, with _Manage Voice Chats_ and _Delete Messages_ permissions.

### 
## Heroku

Read this -> https://t.me/TGVCSupport/17542

#### Generate String session [IMPORTANT]

Download this file [generate_string_session.py](https://raw.githubusercontent.com/thehamkercat/Telegram_VC_Bot/master/generate_string_session.py)



[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/thehamkercat/Telegram_VC_Bot/tree/master)


Send [commands](https://github.com/thehamkercat/Telegram_VC_Bot/blob/master/README.md#commands) to bot to 
play music.





## Commands
Command | Description
:--- | :---
/help | Show Help Message.
/skip | Skip Any Playing Music.
/play [SONG_NAME] | To Play A Song Using Saavn.<br>Service used can be changed in config (`DEFAULT_SERVICE`).
/play youtube/saavn [SONG_NAME] | To Play A Song Using Specific Service.
/play [with reply to an audio file] | To Play A Song With TG Audio File.
/queue | Check Queue Status.
/delqueue | Deletes Queue List and Playlist.
/playlist [songs name separated by line] | Start Playing Playlist.
/joinvc | Join Voice Chat.
/leavevc | Leave Voice Chat.
/volume [1-200] | Adjust Volume. ko
/pause | Pause Music.
/resume | Resume Music.










