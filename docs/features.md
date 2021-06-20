# Features and commands

This bot has many features from random fun commands to helpful moderation tools.  
This part of the documentation shows all kinds of commands and things with descriptions.


## Configuration  
  
This bot comes with some configuration on it. You can change things like prefix and more coming soon.

### a!prefix <prefix>
Changes the prefix for your server.
Example: `a!prefix t!`  

### a!config
Shows the configuration for your server.

### a!set  
Sets config values (Such as mod logging.)  

##### modch <text channel>
Changes where moderation logs (ban, kick, etc.) goes.  

##### events <text channel>  
Changes where event logs goes. (Such as config updates and message logging)  

##### msglogs <enable | disable>  
Enable or disable message logs. (edits and deletes)  

### a!reset  
Resets config values (Such as event logging.)  

##### modch
Resets the mod log channel value.  

##### events <text channel>  
Resets the event log channel value.  

---

## Fun

Fun commands are things like emotes, random games, and others.  

#### a!fox [Fox type]
Get a random fox image.  
You can also get a random fox image of a specific type.  
Example: `a!fox fen`

> **Fox types:**  
> Fennec / Fen  
> Arctic / White / Snow  
> Red  
> Gray / Grey  

!!! tip "Don't ping me, bro."
    For a lot of the emote commands, you do not need to ping someone.  
    You can simply type a server member's name and commands like `a!slap` will function just fine.  
    Example: `a!slap Odaya`  
        
    It even works with nicknames as well! Keep note that it is CaSe-SeNsItIvE.

#### a!boop [member]
Boop a friend or someone random in a server.
Usage: `a!boop @Odaya#8088`

#### a!slap [member]
Slap your friends and other members in a server.  
Usage: `a!slap @Odaya#8088`

#### a!pat [member]
Give your friends a nice pat on the head.
Usage: `a!pat @Odaya#8088`

!!! tip "Sometimes there is nobody around..."
    You can use these commands on yourself.  
    But you also can do just the emote command and it'll do something different.

#### a!hug [member]
Give somebody a hug. Especially when they need one!
Usage: `a!hug @Odaya#8088`

#### a!uwu
You know you want to.  

#### a!kill [member]
Kill someone with a random death message
Usage: `a!kill @Odaya#8088`
---

## NoNitro™  
Be able to use custom emojis (included animated ones) without the need for Discord Nitro.  
(Tho you should still try and get Nitro bc you're supporting the platform you're using.)

#### nmsg:
Converts any {bracket  emotes} into real physical emotes from an emote pack.  
Usage: `nmsg: Wow. I love Portal {as}`  

!!! warning "NoNitro relies on webhooks for this to work."
    Please be sure to have the bot create and manage webhooks in addition to use external emojis.  
    You can disable this for your server using a!disable.

!!! danger "NoNitro isn't available yet."
    We will announce when this feature becomes available.
---

## Extras
Small commands such as a!info.

!!! warn "This is a core module"
    You cannot disable this.

#### a!info
Get basic info on the bot.  
This includes helpful links, the bot version, and its uptime.

#### a!uptime
Dedicated uptime command to show how long the bot has been online for.  

#### a!guildinfo  
Gives information about your server.  

#### a!userinfo
Gives information about a member.  

