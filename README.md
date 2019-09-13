# Thrall-Bot-Cheat-Sheet
This repository is a cheat sheet for the Carl-Bot (renamed Thrall) on the <Get Murked City> discord server.  This does not contain all of the commands available, just the most useful ones.  For a more comprehensive list of commands and functions, you can check out the documentation for Carl-Bot at https://docs.carl.gg/.  You can also access the carl-bot dashboard from the dropdown menu at the main website at https://carl.gg/.

## Introduction

Carl-Bot, also known as **Thrall**, is a discord bot that is employed on our discord server.  There are many different ways that Thrall-bot can be used including auto-moderating the server/channels, giving your user base roles based on emoji specific reactions, and even supplying fun/entertainment based functionality ("~catbomb" command).  However, I will focus on what I think will end up being the most useful (or most used) commands and functions for our use-case.

## Commands

For discord, any bot that is installed will have a set list of commands that can be used.  Thrall-bot commands all start with a prefix.  The Carl-bot default prefix is an exclamation mark (!), but I have configured Thrall-bot to use "**~**" as it's command prefix.  Below I've listed some of the commands that I find useful or fun.

### Moderating

* **ignore/unignore [channels...] [commands..]** - Ignores/unignores the given commands in one or more channels.  If no commands are given, then all of the commands are used.  If no channel is given then the current channel is used.
* **plonk/unplonk [users..]** - Bans/unbans a member from using the bot.
* **plonks** - Displays all plonked users.
* **warn <@member> [reason]** - Warns a user, pms them the reason.
* **mute <@member> [time] [reason]** - Mutes a member (using the muterole, read above) for the specified time.
* **unmute <@member>** - Unmutes a member.
* **ban <@member/ID> [days=2] [reason]** - Bans the member from the server for a number of days and for a specific reason.
* **kick <@memeber> [reason]** - Kicks a member.

### Welcome and Leave Messages

* **set welcome [#channel]** - Sets the channel where welcome/leave/banmsg messages will be posted.
* **welcome [text]** - Sets up a welcome message that will be sent when a new user joins.
* **farewell [text]** - Like *~greet*, but for people leaving.
* **banmsg [text]** - Like *~greet*, but for people getting banned.
* **[dmjoin|pmjoin|joindm|joinpm] [text]** - Like *~greet*, except it dms the message to the user upon joining
* **testgreet** - Not sure how your welcome/farewell/dm messages actually look? Just type !testgreet and have the bot spit out all of them.

### Useful

* **echo [#channel]** - Makes the bot say something in the specified channel.
* **coinflip** - Flips a coin.
* **roll**  - Works like the wow version ~roll [[lower-]upper].
* **urbandictionary [word]** - Looks up the definition for a word on urban dictionary.
* **temp [location]** - Shows some weather information for a specified location.
* **suggest [text]** - Creates a suggestion in the #feeback channel.
* **remind [text]** - Reminds you of something after a certain amount of time. The input can be any direct date (e.g. YYYY-MM-DD) or a human readable offset. Examples: - "next thursday at 3pm do something funny" - "do the dishes tomorrow" - "in 3 days do the thing" - "2d unmute someone" Times are in UTC.
* **poll [question]** - Creates a yes/no poll where you vote with reactions
* **quickpoll [<question> /| <answer> /| <answer>]** - Use pipes ("|") or commas to separate the questions and answers. The first arg is the question, all after that are individual answers.

### Fun 

* **aww** - Post a cute image.
* **cat** - Post a cute image of a cat.
* **dog** - Post a cute image of a dog.
* **avatar <@member>** - Shows a larger image of the avatar of a mentioned user.
