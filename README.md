# Pfizer music bot 
A Telegram Userbot to play Audio and Video songs / files in Telegram Voice Chats.

<div align="center">
  <img src="https://i.pinimg.com/originals/83/23/36/8323363c51b84decc792cec2d23a430f.jpg" width="500" height="500">


It's made with [Shalinibots](https://github.com/shalinithasha) and [Pyrogram](https://github.com/pyrogram/pyrogram)


## Requirements
- Python 3.8+
- FFMPEG
- Nodejs v16+


## Deployment

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Local Deploy
1) Installing NodeJS
```bash
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

2) Installing FFMPEG and Git
```bash
sudo apt-get install git ffmpeg -y
```

3) Cloning the Repo
```bash
git clone https://github.com/shalinithasha/pfizermusic
cd TG-MusicPlayer
```

4) Rename `example.env` to `.env` and Fill in the Environment Variables

5) Installing Requirements
```bash
pip3 install -U -r requirements.txt
```

6) Run the Bot
```bash
python3 main.py
```


## Environment Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session. Get one from [Here](https://replit.com/@ThashaKwela/pfizermusicbot#main.py)
- `HNDLR` - Your Userbot Handler (Default is !)


## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `!ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `!help` for commands.


## Credits ✨
- [shalini](https://replit.com/@ThashaKwela) for [Pyrogram](https://github.com/shalinithasha/pfizermusic)

