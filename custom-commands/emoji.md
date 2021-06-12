---
description: this functions return emoji name id ..
---

# emoji Functions

### $emojiCount

returns the Number of emoji your server has

### $emojiID

returns the emoji id the user reacted

### $emojiExists\[emojiID\]

returns true/false true if the emoji exists

### $emojiName

returns the emoji name the user reacted

### $emojiToString

converts the emoji to string the user reacted

### $customEmoji\[emojiname\]

returns the emoji id with name from the given emoji name like &lt;:staff:798798790900970709&gt;

### $emojisFromMessage\[string\]

returns all emoji from the string like 

`$emojisFromMessage[hi🎋hello🎫bye🧵s🎗s🎍v🎐d🎠]`

would output 🎋,🎫,🧵,🎗,🎍,🎐,🎠

### $resolveEmojiID\[name/id/emoji\]

converts  it to the emoji ID

