> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/ZAIBITECH)

# Use Node.Js 18 or greater

## Functionality

| Functional                                                    | Supported |
| ------------------------------------------------------------- | :-------: |
| Auto creating wallet and linking                              |    ✅     |
| Auto completing quests                                        |    ✅     |
| Multithreading                                                |    ✅     |
| Binding a proxy to a session                                  |    ✅     |
| Auto-purchase of items if you have coins (multitap, attempts) |    ✅     |
| Binding a proxy to a session/query_id                         |    ✅     |
| Random sleep time between clicks                              |    ✅     |



| Settings                           | Description                                                                |
| ---------------------------------- | -------------------------------------------------------------------------- |
| **API_ID / API_HASH**              | Platform data from which to launch a Telegram session (stock - Android)    |
| **WORD_PHRASE_LENGTH**             | The length of key phrase to generate for thr wallet (12 or 24)             |
| **AUTO_CREATE_AND_CONNECT_WALLET** | Whether the bot should auto create and connect wallet (True / False)       |
| **REFERRAL_CODE**                  | Referral code to use                                                       |
| **AUTO_COMPLETE_QUESTS**           | Whether the bot should complete quests (True / False)                      |
| **DELAY_BETWEEN_QUEST**            | Delay between quests in seconds (eg. [20, 30])                             |
| **DELAY_BETWEEN_STARTING_BOT**     | Delay between starting in seconds (eg. [20, 30])                           |
| **USE_PROXY_FROM_JS_FILE**         | Whether to use proxy from the `bot/config/proxies.js` file (True / False)  |
| **USE_PROXY_FROM_TXT_FILE**        | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

### More configurations [Click Here](/README-UPDATE.md)

## Installation

You can download [**Repository**](https://github.com/ZAIBITCH1/Paws-Bot) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/ZAIBITECH1/Paws-Bot.git
~ >>> cd Paws-Bot

#Linux and MocOS
~/Paws-Bot >>> chmod +x check_node.sh
~/Paws-Bot >>> ./check_node.sh

OR

~/Paws-Bot >>> npm install
~/Paws-Bot >>> cp .env-example .env
~/Paws-Bot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/Paws-Bot >>> node index.js

#Windows
1. Double click on INSTALL.bat in Paws-Bot directory to install the dependencies
2. Double click on START.bat in Paws-Bot directory to start the bot

OR

~/Paws-Bot >>> npm install
~/Paws-Bot >>> cp .env-example .env
~/Paws-Bot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/Paws-Bot >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/Paws-Bot >>> node index.js --action=1

OR

~/Paws-Bot >>> node index.js --action=2

#1 - Create session
#2 - Run clicker
```
