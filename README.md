# Telegram Bot Vercel Boilerplate

Telegram Bot Vercel Boilerplate based on Node.js and [Telegraf](https://github.com/telegraf/telegraf) framework.

This template inspired by [Telegram Bot Boilerplate](https://github.com/yakovlevyuri/telegram-bot-boilerplate) for easily deploy to [Vercel](https://vercel.com).

[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@7rodma/deploy-a-serverless-telegram-chatbot-using-vercel-57665d942a58)

## Before you start

First copy `.env.example` file to `.env` and fill in all necessary values.

```
TELEGRAM_BOT_TOKEN="<YOUR_BOT_API_TOKEN>"
```

## Start your local server

```
npm ci
npm run dev
```

## Production

You can fork this template and do the necessary changes you need. Then you when are done with your changes simply goto [vercel git import](https://vercel.com/import/git).

Reference to [this update](https://vercel.com/docs/security/deployment-protection#migrating-to-standard-protection), you need turn off `Vercel Authentication`, Settings => Deployment Protection

Feel free to create PR!

## Demo

You can see a working version of the bot at [@Node_api_m_bot](https://t.me/Node_api_m_bot)

## Links

[Public APIs](https://github.com/public-apis/public-apis)
