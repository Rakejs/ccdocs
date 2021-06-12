---
description: Copied from dbd.js docs
---

# Compact functions

**Compact functions are really easy to use they are the replacement for some functions.This functions returns values**

### $msg\[chid;mid;property\] or $msg\[property\]

**Properties**

* author - Message's Author's ID
* authormention - Message's Author's mention
* authortag - Message's Author's tag
* authorname - Message's Author's name
* channel - Message's channel id location
* channelname - Message's channel name location
* cleancontent - Message's content without any mentions \(excludes @here/@everyone\)
* content - Message's content
* created - Message's date and time of creation
* guildid - Message's guild's id of origin
* id - Message's ID
* isdeleteable - Whether or not the author of the command can delete the message, Returns Boolean
* isdeleted - Whether or not the message is deleted, Returns Boolean
* iseditable - Whether or not the author of the command can edit the message, Returns Boolean
* ispinnable - Whether or not the author of the command can pin the message, Returns Boolean
* ispinned - Whether or not the message is pinned, Returns Boolean
* rawcontent - Message's content without ANY mentions
* guildname - Message's guild's name of origin
* url - Message's url

```text
$msg[content]
//will return the content
```

### $role\[rid;property\]

#### Properties

* name - Role's name
* mention - Role's mention
* id - Role's ID
* hex - Role's hex color
* created - Role's date and time of creation
* position - Role's position
* rawposition - Role's raw position
* guild - Role's guild's id of origin
* guildname - Role's guild's name of origin 
* timestamp - How long ago the role was created
* isdeleted - Whether or not the role has been deleted, Returns Boolean
* ismentionable - Whether or not the role can be mentioned, Returns Boolean
* iseditable - Whether or not the author of the command can edit the role, Returns Boolean
* ismanaged - Whether or not Discord manages the role, Returns Boolean
* ishoisted - Whether or not the role is hoisted, Returns Boolean

```javascript
$role[1979790790790789;name]
//returns the name of the role
```

### $user\[uid;property\]

#### Properties

* name - User's name
* id - User's ID
* tag - User's Tag
* discrim - User's discriminator
* mention - User's mention
* avatar - User's avatar URL
* isbot - Whether or not the user is a bot, Return's Boolean
* istyping - Whether or not the user is typing, Return's Boolean
* created - User's date and time of creation
* timestamp - How long ago the user was created
* lastmessageid - User's last message ID
* lastmessagechannelid - User's last channel ID

```javascript
$user[1979790790790789;name]
//returns the name of the user with the id
```

### $channel\[id;property\] or $channel\[property\]

#### Properties

* name - Channel's Name
* topic - Channel's Topic
* ID - Channel's ID
* position - Channel's position organized by categories
* rawposition - Channel's position
* mention - Mention's the Channel
* created - Channel's date and time of creation
* isdeleted - Whether or not the channel has been deleted from the current guild, Returns Boolean
* type - Channel's Type - text, voice, category
* timestamp - How long ago the channel was created
* guildid - Channel's home guild's id
* guildname - Channel's home guild's name
* ismanageable - Whether or not the the author of the command has permission to manage the channel, Returns Boolean
* parentid - Channel's category's id
* parentname - Channel's category's name
* isviewable - Wehther or not the author of the command can view the channel, Returns Boolean
* isdeleteable - Whether or not the author of the command can delete the channel, Returns Boolean

```javascript
$channel[797907907097907;name]
//returns the name of the channel
```

### $guild\[property\]

guild = Discord Server

#### Properties

* name - Guild's Name 
* id - Guild's ID
* acronym - Guild's name acronym
* afkchannelid - Guild's AFK Channel's ID
* boostcount - Guild's boost count
* boostlevel - Guild's boot level
* created - Guild's date and time of creation
* description - Guild's description
* emojicount - Guild's emoji count
* isavailable - Whether or not the guild is available, Returns Boolean
* isbotremoved - Whether or not the bot is in the guild, Returns Boolean
* ispartnered - Whether or not the guild is partnered, Returns Boolean
* isverified - Whether or not the guild is verified, Returns Boolean
* membercount - Guild's member count
* ruleschannel - Guild's rule channel's id
* systemchannelid - Guild's system channel's id
* timestamp - How long ago  the guild was created
* updateschannel - Guild's moderator news channel's id
* verificationlvl - Guild's verification level

```javascript
$guild[name]
//returns the guildname
```

### $emoji\[emojiID;property\]

#### Properties

* name - Emoji's name
* id - Emoji's id
* created - Emoji's date and time of creation
* url - Emoji's URL
* identifier - Emoji's name:id
* isanimated - Whether or not the emoji is animated, Returns Boolean
* isdeleted - Whether or not the emoji is deleted, Returns Boolean
* guildid - Emoji's guild of origin
* ismanaged - Whether or not the emoji is a custom or discord default emoji, Returns Boolean

```javascript
$emoji[789789790790808;name]
//returns the emoji name
```



