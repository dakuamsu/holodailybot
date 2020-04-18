# Holodailybot

Unofficial Hololive-style gacha bot on Telegram. Revised.

[![](https://img.shields.io/badge/Telegram-%40holodailybot-blue.svg)](https://t.me/holodailybot)

## Usage

```
export PORT=3000
export TELEGRAM_BOT_KEY=BOT_KEY
npm install
npm run build
npm run run
```

Also, we have a `ecosystem.config.js` for [`pm2`](https://pm2.io) users.

## Contribute

Currently we need help on:

* [`birthday.change.ts`](https://github.com/suisei-cn/holodailybot/blob/master/src/middlewares/birthday.change.ts): For Hololivers birthdays so that a Hololiver will be always present on his/her birthday as a celebration.
* [`hololiverInfo.ts`](https://github.com/suisei-cn/holodailybot/blob/master/src/hololiverInfo.ts): For Hololiver's memes.

## Golden Fingers

The demo instance of @holodailybot on Telegram includes a special undisclosed middleware which contains some golden fingers. Try interacting with the bot and dig surprises!

## License

MIT
