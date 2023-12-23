# Radio Javan Downloader

Download [Radio Javan](https://play.radiojavan.com/) media only by its URL!

## Features

Currently, this bot supports downloading:

- Tracks
- Podcasts
- Videos

You can also donate to this project to add more features, such as downloading playlists!

## Use

I have this bot in production which you can use it for free [here](https://t.me/rjripbot).

## Run

### Create a Bot

Use Telegram's [BotFather](https://t.me/BotFather) and register for a new bot. Copy your bot API token at the end.

### Setup

copy and paste this line onto your server:

```bash
bash <(curl -sSL "https://bit.ly/rj-dl")
```

- This script installs nodejs and the projects dependencies.
- It installs [PM2](https://pm2.io) for running your bot as a production service.

### Test

- Clone the repo

```bash
git clone https://github.com/AlirezaBaratian/rj-dl.git 
cd rj-dl
```

- Install dependencies

```bash
npm i
```

- Declare your bot token in .env

```bash
echo "BOT_TOKEN=<your-bot-token>" > .env
```

- Run the script

```bash
node bot.js
```

## Credits

- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api)
- [mongoose](https://github.com/Automattic/mongoose)

## Donation

If you found this project helpful, you ca definitely donate:

TRON network (TRC20): `TAB77BR4b6qPTnqoeBJxaXsoidSZN36mEu`

## Contribution

Feel free to submit issues and PRs.
