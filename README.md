# Crident VPS Bot
This is an example bot you can use for your VPS on crident.com

## Configuration Options

### Prefix:

This is the prefix you want the bot to use, it can be absolutely anything. It is recommended to use something common like `!`, `-`, `?`.

### Token: 

This is the bot token you can get from completing the following steps:

1. Head over to https://discordapp.com/developers/applications/

2. Hit the plus symbol and create a new application like the following:

![alt text](https://i.crident.net/690d08.png "Create Application")

3. Add a profile picture for your bot: (this step is not mandatory, though advised).

![alt text](https://i.crident.net/6e14cd.png "Profile Picture")

4. Click bot which can be found here:

![alt text](https://i.crident.net/68c5d2.png "Bot Tab")

5. Create a bot user:

![alt text](https://i.crident.net/12508b.gif "Create bot user")

6. Uncheck the Public Bot option, copy the token & hit save:

![alt text](https://i.crident.net/593a60.gif "Token")

Once you have obtained your token simply place it in config.json in the correct place.

### Staff Roles: 

In this section you should include the IDs to any staff roles you wish to have access to the commands (provided you have them enabled).

### Logging Style: 

You can have this one of two ways, either embeds or plain text. Here are some examples:

Embeds:

![alt text](https://i.crident.net/00a682.png "Embeds")

Plain Text:

![alt text](https://i.crident.net/335e81.png "Plain Text")

Simply place the style you like, example: `"logging_style": "embed"` or `"logging_style": "text"`

### Moderation Commands:

This is simple, either put true or false depending on what you would like. The moderation commands are as follows:

* Purging

* Warning

* Temporary Mute

* Permanent Mute

* Kick

* Temporary Ban

* Permanently Ban

* Unmuting

* Unbanning

### Miscellaneous Commands:

This is simple, either put true or false depending on what you would like. The miscellaneous commands are as follows:

* User Information

* Server Information

* Last Seen

* Reminders

### Word Blacklist

This is simple, either put true or false depending on what you would like.

### Word Whitelist

This is simple, either put true or false depending on what you would like.

### Name Blacklist

This is simple, either put true or false depending on what you would like.

### Word Blacklist

This is simple, either put true or false depending on what you would like.

### Moderation Logging

This is simple, either put true or false depending on what you would like.

### Censored Logging

This is simple, either put true or false depending on what you would like.

### Moderation Logging Name

This is simple, put the name of the channel you'd like to use for mod-log here. Note, you must have Moderation Logging set to true above.

### Censored Logging Name

This is simple, put the name of the channel you'd like to use for censored-log here. Note, you must have Censored Logging set to true above.
