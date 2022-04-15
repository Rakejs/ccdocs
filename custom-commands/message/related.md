---
description: here you can find related functions
---

# related functions

### $sendMessage\[msg;return id (yes/no)]

sends a message to the channelUsed

### $sendWebhook\[hookid;hooktoken;message;options...]

sends a message with the Webhook\


```
$sendWebhook[hookid;hooktoken;hi!;{title:Embed}]
```

you can send more then one message by adding a ; and the second message or embed

### $sendCrosspostingMessage\[msg;chid1;chid2;...]

send a message to multiple channel

### $editMessage\[msgid;new msg;chid(optional)

edits the message with the id.Channelid is default is channelUsed

### $editIn\[time(s/m/h/d);message]

edits the message that the bot send

### $clear\[amount;filter;chid(optional)]

delete message with the given amount.The chid is default channelUsed.Do not forget to set Minperms

### $pinMessage\[channelid;messageid] or $pinMessage

pins the message with given ch/msg id or the current message

### $unPinMessage\[channelid;messageid]&#x20;

unpins the message(if pinned) with given ch/msg id&#x20;

### $noEscapingMessage

special Character won't be escaped anymore like \\

### $noMentionMessage

This function removes all mention from the author message and returns it\
like: $noMentionMessage . The User types Hello @Rake the Bot will return Hello

### $attachment\[link]

this functions attach a File like a image or video...&#x20;

### $webhookExists\[hookid;hooktoken]

this returns true if the webhook with the given id and token exist else it will return false

### $removeContains\[channelID;limit;word1;word2;...]

deletes all message with the word in the channel

### $deletecommand

deletes the trigger of the message

