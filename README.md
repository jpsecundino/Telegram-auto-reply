# autoreply
A script to auto reply private messages on telegram with a fixed message. It's simple to modify and make it respond to group/channel messages as well. Check the [Telethon](https://telethon.readthedocs.io/en/latest/index.html) documentation.

### How does it work?
  You only need to get the api_id and the pai_hash from the [Telegram Core](https://my.telegram.org/auth?to=apps).
  After you create your new app, you'll have access to these items.
  
  You just need to replace these items in the right places, put your username (your nickname without @) in the 'Username' location, choose the automatic message to show when someone sends you a message and run the program. It will be waiting for a private message to reply it.

```
api_id = 'put your api_id here'
api_hash = 'put yout api_hash here'

client = TelegramClient('Username', api_id, api_hash)

message = 'Hey, I'll be at a retreat until Saturday. I promise to get in touch as soon as I can. See you.'

```

### Made with:
[Telethon](https://telethon.readthedocs.io/en/latest/index.html)
