# Discord Game Of Life Bot

A simple bot that creates a 12x12 Conways Game of Life (gol)

## Usage

### Running the bot

This example uses bot tokens for authentication only. While user/password is supported by DiscordGo, it is not recommended for bots.

```bash
./discordgol --help

Usage of ./discordgol:
  -t string
        Bot Token
```

The below example shows how to start the bot

```bash
./discordgol -t YOUR_BOT_TOKEN
Bot is now running.  Press CTRL-C to exit.
```

### Interacting with the bot

Send "gol" to the channel you want to see a gol in

React with 🔴 to stop the playback

## TODO
- [ ] Configure the size of grid
- [ ] Rubbish Tin to delete
- [ ] React with ⏸ and ▶ to control automatic playback
- [ ] React with ⏪ and ⏩ to go to previous and next iterations
