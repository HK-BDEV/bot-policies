# PandaPong Privacy Policy

_Last updated: 9 October 2026_

PandaPong ("the bot") is a Discord bot for players of the EPIC RPG game bot. It sends cooldown reminders, event pings and stats, and runs giveaways. This policy explains what data the bot uses, what it stores and why.

## What the bot reads
- **EPIC RPG commands typed by users** (for example `rpg hunt`) and **EPIC RPG's replies**, to know which command was used, when to remind the user, and to count daily command usage.
- **EPIC RPG event messages**, to ping the server's event roles.
- **Messages that start with the bot's prefix** (`r`), so it can respond to commands.

Message content is processed to run these features. The bot does **not** keep a log or copy of users' messages.

## What the bot stores
The bot keeps the following in its database on our server:

| Data | Why | How long |
|---|---|---|
| Discord user ID and username | To link the data below to the right user | As long as the related data exists |
| Pending reminders (which command, channel, time) | To send the reminder | Deleted once the reminder is sent, or with `rdelreminders` |
| Reminder settings | To remember which reminders a user turned on or off | Until the user changes them or asks for deletion |
| Daily EPIC RPG command counts | For `rstats`, leaderboards and usage stats | Kept for all-time stats, deleted on request |
| Tracked inventory amounts (rubies, seeds) | For `rinventory` | Until the user asks for deletion |
| Horse breeding attempts and optional proof links | For horse tracking | Until the user asks for deletion |
| Server settings (channels and roles for pings) | To configure the bot per server | Until the server changes them or removes the bot |
| Scheduled giveaways and announcements | To post them at the right time | Deleted after posting, unless set to repeat |

No passwords, emails, payment details or message history are stored.

## Your choices
- **`rdisable`** turns off reminders and command tracking for you. **`renable`** turns them back on.
- **`rconfig`** lets you choose which reminders you get.
- **`rdelreminders`** deletes your pending reminders.
- Server admins choose which channels the bot can see.
- You can ask for all your stored data to be deleted at any time (see Contact).

## How data is used and shared
- Data is used only to provide the bot's features.
- Bug reports sent with `rbug` (text and image links) are forwarded to a private channel for the developers.
- Data is never sold, never used to train AI or machine learning models, and never shared with third parties except Discord itself.

## Contact
Open an issue at [github.com/HK-BDEV/bot-policies/issues](https://github.com/HK-BDEV/bot-policies/issues) for questions or data deletion requests.

## Changes
We may update this policy. The date at the top shows the latest version.
