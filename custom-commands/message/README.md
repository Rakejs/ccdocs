---
description: this function returns message value
---

# Message functions

> Message Functions  
> $message, $messageAttachment ,$messageExists $messageFlags, $messageSlice, $messageType ,$messageWebhookID,$messageID,$filterMessage

### $message\[numberofargs\] or $message

will return the message of the user or the argument position

### $messageAttachment

returns the message Attachment url

### $messageExists\[channelid;messageid\]

returns a boolean true/false .If the messageExists it would return true

### $messageSlice\[x;y\(optional\)\]

slices the message from x or from x to y

### $messageType

returns the message Type

### $messageWebhookID

returns the message webhook id

### $messagePublish\[channelid;messageid\] or $messagePublish

publishes the message in a announcement channels with given channel and message if or the currentchannel

### $messageID

returns the message id of the message sent by the user

### $filterMessage\[text;val1;val2\]

this function removes the value from the text

### $awaitMessages\[id;time\(s\);everything;token;Command Timed out\]

starts a message collector and collects the message and executes the cc with the token





