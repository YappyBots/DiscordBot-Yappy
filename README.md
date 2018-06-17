# Yappy, the Github Monitor

[![Online Users in Yappy Discord Server](https://discordapp.com/api/guilds/231548941492027393/embed.png)](https://discord.gg/HHqndMG)
[![Yappy: David (Dependencies Status)](https://img.shields.io/david/datitisev/DiscordBot-Yappy.svg?maxAge=2592000)](https://david-dm.org/datitisev/DiscordBot-Yappy)
[![Yappy: Codacy Badge](https://api.codacy.com/project/badge/Grade/950ed41fd5b6417d9cc83f332d93e0ef)](https://www.codacy.com/app/datiti/DiscordBot-Yappy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=datitisev/DiscordBot-Yappy&amp;utm_campaign=Badge_Grade)

Monitor your github repos by adding this bot to your server, set up a channel for it, and don't miss any events!

### Info

Join our Discord server at https://discord.gg/HHqndMG

Invite the bot at http://bit.ly/DiscordYappyGithub

### Commands

Prefixes are `G! ` (with space), custom prefix set up, or mention the bot.


__**Util**__:
  - `help` - a help command... yeah :P
  - `invite` - how to invite the bot and set up github events!
  - `clean` - cleans the bot's messages found in the last 100 messages
  - `ping` - uh... ping? pong!
  - `stats` - shows the stats of the bot... what else?

__**Github**__:
  - `issues search <query>` - search issues by any field in the global repo
  - `issue <number>` - gives info about that specific issue in the global repo
  - `pr search <query>` - search pull requests by any field in the global repo
  - `pr <number>` - gives info about that specific pr in the global repo
  - `release <query>` - gives info about a release that matches that query in its tag in the global repo

__**Admin**__:
  - `conf [view]` - views the server's config
  - `conf get [key]` - gets a specific config key in the server's config
  - `conf set <key> [value]` - sets the key to the value, `repo`'s value may be none to disable
  - `init <repo>` - initialize repo events on channel
  - `remove` - remove repo events on channel

### Developer Documentation

https://www.yappybots.tk/#/docs/yappygithub/
