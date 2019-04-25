# PyroBot - A help page

## General Information

This program is a Userbot for the [Telegram Messenger](https://telegram.org) based on [Pyrogram](https://github.com/pyrogram/pyrogram).

## Features

### First Commands (`1start.py`)

* `.alive` - Tells you that the bot is running
* `.help` - Gives out a link to this document

### Administration (`admin.py`)

These work only in reply to another user.

* `?ban x` - Bans a replied-to user for time `x`
* `?unban` - Unbans a replied-to user
* `?mute x` - Mutes a replied-to user for time `x`
* `?unmute` - Unmutes a replied-to user
* `?kick` - Kicks a replied-to user

Timed restrictions can be applied in the following scheme:

* `1d` - 1 day
* `2h` - 2 hours
* `3w` - 3 weeks

### Evaluation (`evaluation.py`)

Evaluate and Execute whithin Telegram

* `.eval <query>` - Evaluate a string of x (e.g. `message.chat.title` for chat title)
* `.exec <query>` - Execute a string of x. This is recommended for executing `send_*`, since it would doxx your phone number.

### Information (`get_info.py`)

Get information about your administration and chat

* `!admins` - Gives out a list of all admins in a chat
* `!members` - Gives out counter of all members, bots and deleted accounts in that group.

### Memes (`memes.py`)

* `dog` - Sends an image of a dog 🐶🐕

### Miscellaneous (`misc.py`)

* `.up` - Gives out the current uptime of the bot.

### Steam (`steam.py`)

* `?steam` - Gives a clean Steam Account

### Who Is ...? (`whois.py`)

* `.whois` - Gives out information about a user

### World Wide Web (`www.py`)

* `.speed` - Run a speedtest
* `.dc` - Give out information about the closest Telegram Datacenter to you
* `.ping` - Milliseconds between two instant edits (The latency to Telegram)