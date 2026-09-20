---
label: Discord Bots
icon: dependabot
order: 300
---
# Discord bots

We use a mix of bots to give our server unique and helpful features. Most of our bots are in-house and open source with a few reputable exceptions.

## John Helldiver
John Helldiver is our main bot. Its functions include the following:
- Enables trusted community members to update and/or restart our game servers.
- Serves as an AI chatbot with direct access to many Bomb Squad related resources. (All public HD2 data, HD2 steam patch notes, all Bomb Squad game server uptime statuses, and this very wiki)
- Other semi-secret stuff that you will have to look through the source files if you want to learn.

### How to use
To interact with John Helldiver you must ping him. He can remember up to 6 messages in the past, separated by channel. With every interaction, a 12-hour channel-specific timer is started/reset. If said timer ever reaches 0, John's memory will be wiped for that channel.

### Technical info
John is powered by [n8n](https://github.com/n8n-io/n8n), [Gemini 3.5 Flash Lite](https://aistudio.google.com/usage), and the [Helldivers 2 API](https://github.com/helldivers-2/api). His source files are available [here](https://github.com/TankObliterator/john-helldiver) and are automatically updated every day at 6 AM MST.

## Carl-bot
Carl-bot, aka "Automaton 1", has been in the server since almost the beginning and only has one purpose: announcing new member joins and leaves. See their [website](https://carl.gg/) for more info.

## Music Bot
The Music Bot can only be described as a vile beast that has to be constantly forced into submission. It is a self-hosted instance of [Vocard](https://github.com/ChocoMeow/Vocard) with a pretty normal Lavalink backend.

!!!base Note on Music Sources
Currently, we support playing from any™ source that isn't Apple Music or Spotify (this could change if someone with Spotify Premium or an Apple developer account is willing to generate an API key).
!!!