---
description: >-
  this function returns value or executes action ,check related functions for
  more
---

# Channel functions

> List of Channel functions\
> $channelCategoryID, $channelCount, $channelExists, $channelID, $channelName, $channelNSFW, $channelSendMessage, $channelTopic, $channelType, $channelUsed,$channelPermissionsFor,$systemChannelID

## $channelCategoryID\[channelid] or $channelCategoryID

returns the category id the channels belong or with a given id

## $channelCount\[voice/text/category] or $channelCount

returns the count of channel with types like $channelCount\[voice] would return the numbers of the voice channel or just whole count without parameter

## $channelExists\[channelid]

returns true/false. Checks if the channel with the given id exists

## $channelID\[channelname] or $channelID

returns the channel id of the Used channel or by searching with a channel name it would return the id of it

## $channelName\[channelid] or $channelName

returns the name of the channel from the given id or the channel used

## $channelNSFW\[channelid] or $channelNSFW

returns if the channel is a nsfw channel true/false or with the given id

## $channelSendMessage\[channelid;yourmessage;return messageid(yes/no)]

send a mesage to the channel. You can return the messageid to edit again

## $sendMessage\[yourmessage;return messageid(yes/no) (needed!!)]

Sends a mesage to the channel, set in $channelUsed. You can return the messageid to edit again

## $channelType\[channelid] or $channelType

returns the channel topic from the given id or the channel Used

## $channelTopic\[channelid] or $channelTopic

returns the channel type from the given id or the channel Used

## $channelUsed\[channelid]

returns the used Channel, or changes the Channel used setting to the ID specified in the between the \[ ]

## $channelPermissionsFor\[channelid(optional),userid]

returns the channel Permission for the user with given channel id or channelUsed

## $systemChannelID

returns the system channel id of the guild .Mostly the first channel

## $DM\[userID(optional)]

Redirects text in the code to the DM of a user

{% hint style="warning" %}
This function is PREMIUM Only
{% endhint %}

## $sendDM\[userID;message;return messageid(yes/no)]

sends a message to the DM of a user

{% hint style="warning" %}
This function is PREMIUM Only
{% endhint %}
