---
description: gets a Value from Object or ...
---

# get Functions

> List of get Functions:  
> $getChannelSlowmode,$getEmbed,$getMessage,$getObject,$getObjectProperty,$getReactions,$getRoleColor,$getServerInvite,$getTextSplitLength,$getUserBadges

### $getChannelSlowmode\[channelid\] or $getChannelSlowmode

gets the Slowmode for the channel in the given id or the channelUsed

### $getEmbed\[channelid,messageid,options\(optional\)\]

pls check Options-&gt; embeds .This will output the value you need like description would output the Description of the Embed

### $getMessage\[channelid,messageid,options\(optional\)\]

pls check Options-&gt; message .This will output the value you need like content would output the content of the message

### $getObject

outputs all object property

### $getObjectProperty\[key\]

outputs the value of the added Key 

### $getReactions\[channelid;messageid;emoji;mention/username/id\]

returns which user reacted on the message with the emoji in type of mention id or name you have choose

`$getReactions[638263892081;3186381263882;🧨;id]`  
would output 68968879890434344,6778667867867867

### $getRoleColor\[roleid\]

outputs the role color in hex

### $getServerInvite

outputs a invite and creates one if there are none

### $getTextSplitLength

returns the length of a Text

```javascript
$getTextSplitLength 
$textSplit[abc.def.ghi;.]
// would output 3
```

### $getUserBadges\[userid\]

output the badges the user has like `$getUserBadges[34334232434232]` would output House of Balances

