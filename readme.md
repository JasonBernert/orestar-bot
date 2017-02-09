# ORESTAR Bot

ORESTAR bot is a [Slack](readme-slack.md) bot that delivers Oregon campaign finance data from the  [ORESTAR](https://secure.sos.state.or.us/orestar/gotoPublicTransactionSearch.do) database. ORESTAR bot interfaces with [HackOregon's](http://www.hackoregon.org/) [Behind The Curtain](http://behindthecurtain.hackoregon.com/#/) API. You can learn more about the API [here](https://github.com/hackoregon/btc-backend/blob/master/endpoints/endpoint_use_readme.md). ORESTAR bots is built with [Botkit](https://github.com/howdyai/botkit).

## Getting Started

1. **Download or clone ORESTAR bot:** `git clone https://github.com/JasonBernert/orestar-bot.git`
2. **Install dependencies:** `npm install`
3. **Create a new bot integration** for your team [**here**](https://my.slack.com/services/new/bot). Though you can name the bot whatever you'd like, `@orestar` will be the name of the bot in this documentation.
4. **Copy the API token** that Slack gives you for your new bot.
5. **Run ORESTAR bot** using the token you just copied: `token=REPLACE_THIS_WITH_YOUR_TOKEN node orestar_bot.js`
6. ORESTAR bot should be online! Within Slack, send it a quick direct message to say `hello`. It should say hello back!

Type: `/invite @orestar` to invite your bot into a channel.

## What can ORESTAR bot do?

ORESTAR bot responds to the following phrases:

`top five` gets the total contributions from the top 5 contributing individuals, for all recipients, in all of Oregon.

More coming soon...
