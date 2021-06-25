---
description: this functions add Reaction/Emoji/Object
---

# add Functions

> $addCmdReactions, $addEmoji, $addMessageReactions ,$addObjectProperty ,$addReactions

### $addCmdReactions\[🎁;😉\]

Add reaction to the trigger. You can add multiple reactions by adding `;` after each emoji.

### $addEmoji\[url;name;return emoji yes/no\(optional\)\]

Adds an emoji to the server. The URL of the emoji must be under 300 kb size and should end with `.gif/.png/.jpg`. You can return emoji to check it.

### $addMessageReactions\[chid;msgid;emoji1;emoji2\]

Add a reaction to the message using it's ID. You can add multiple reactions by adding `;` after each emoji.

### $addObjectProperty\[key;value\]

Add properties\(key\) to an object that you have created. Check create Object.  


### $addReactions\[🎁;😉\]

Add reactions to the message that the bot sent. You can add more then one Reaction by adding `;` after each emoji

```text
Gift
$addReactions[🎁;😉]
```

![add Reaction Command](../.gitbook/assets/image%20%2829%29.png)

