# VideoScraperBot
A telegram bot that uses the command line utility [youtube-dl](https://github.com/rg3/youtube-dl/) to download videos from YouTube.com and other video sites.
This project is still under development

## Requirements 
* Python 3+
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
  * Install via pip: pip install python-telegram-bot --upgrade
* [youtube-dl](https://github.com/rg3/youtube-dl/)
  * Install via pip: sudo -H pip install --upgrade youtube-dl
* ffmpeg
  * Ubuntu: sudo apt-get install ffmpeg
## Config
* admin_chat_id: bot admin
* user_chat_id: users that are allowed to use the bot
* video_path: location of the downloaded video files
* audio_path: location of the downloaded audio files
* ftp_site: your website along with the directory where you are downloading the videos example https://mysite.com/mp4/' (used for large video files)
## Commands
* Simply just send a link to download the video
* \mp4 followed by a link to download a video
* \mp3 followed by a link to download an audio
* \request to request access to the bot, the request will go to the Admin
* \test check if the bot is working
## Running the bot
`python3 scraper.py`
