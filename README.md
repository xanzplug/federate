<h1 align="center">Federate</h1>

<p align="center">
  A Discord bot for moderation, music, giveaways and everyday server tools.<br>
  Free to add to your server.
</p>

<p align="center">
  <a href="https://discord.com/oauth2/authorize?client_id=1543491783814545418&permissions=564325889993942&integration_type=0&scope=bot+applications.commands"><b>Add to Discord</b></a> ·
  <a href="https://discord.gg/EMgyRjfaAH">Support server</a>
</p>

---

Federate started as a bot called Sway that I rebuilt from scratch. It's built with Node.js and discord.js, and every command replies with a clean card instead of a wall of text.

The source code isn't public. This repo is where the bot lives on GitHub: what it does, how to set it up, and where to get help.

## Commands

Every command works as a slash command and with your server's text prefix (for example `,help`).

**Moderation**
- `/hardban` ban someone permanently so they can't be unbanned
- `/jail` move someone into a jail channel
- `/strip` and `/staffstrip` remove someone's roles, with a reason
- `/nuke` clear a channel by deleting it and bringing it back fresh
- `/slowmode` set or turn off slowmode in a channel
- `/botclear` delete the bot's last 10 messages in a channel
- `/honeypot` catch raiders and spam bots with a trap channel (ban, kick or softban)
- `/verification` make new members verify before they can talk
- `/incidents` see recent moderation incidents

**Server setup**
- `/setup` set up the muted role and logs in one go (`/setup reset` to start over)
- `/log status` see which events are being logged, grouped by category
- Welcome messages with your own title, message, thumbnail and link buttons
- `/customize` give the bot its own avatar and banner in your server
- `/emoji list` and `/emoji remove`
- `/media` give or take someone's permission to send files

**Music**
- `/play`, `/skip`, `/stop`, `/pause`, `/resume`, `/queue`, `/nowplaying`, `/loop`, `/volume`, `/shuffle`, `/remove`

**Fun and utility**
- `/giveaway` create, end, reroll, cancel or list giveaways
- `/afk` set an AFK status
- `/say` have the bot post a message
- `/permissions` check what permissions a member has
- `/invite` and `/help`

## Getting started

1. [Add Federate to your server](https://discord.com/oauth2/authorize?client_id=1543491783814545418&permissions=564325889993942&integration_type=0&scope=bot+applications.commands).
2. Drag Federate's role near the top of your role list. It can only manage roles that are below its own, so jail, strip, `/media` and verification need this.
3. Run `/setup`, then `/help` to see everything.

## Help and feedback

Questions, bugs or ideas: join the [support server](https://discord.gg/EMgyRjfaAH) or [open an issue](../../issues).
