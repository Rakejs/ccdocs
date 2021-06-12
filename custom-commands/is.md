---
description: This functions returns a Boolean(true or false)
---

# is Functions

> List of is functions:  
> $isBanned, $isBoosting ,$isBot ,$isDeafened ,$isHoisted ,$isManaged, $isMentionable, $isMentioned, $isMuted ,$isNumber ,$isUserDMEnabled ,$isValidHex, $isValidInvite ,$isValidLink, $isValidObject,$isemoji

## $isBanned\[userid\]    

returns true or false.If the user is banned it will return true if not then it will return false

## $isBoosting\[userid\] or $isBoosting    

returns true or false. This checks if the user is Boosting the Server if the User is Boosting the Server it will return true.You can check Boosting from other User too by checking it with a param like: `$isBoosting[userid]`  just replace user id with the id

## $isBot\[userid\] or $isBot 

returns true or false. This checks if the user is a Bot .If the User is a Bot. It will return true.You can check  if  other users is a bot by adding a parameter like: `$isBoosting[userid]`  just replace user id with the id

## $isDeafened\[userid\] 

returns true or false. This checks if the user is a Bot .If the User is deafened. It will return true.

## $isHoisted\[roleid\] 

returns true or false. This checks if the role is hoisted . It will return true, if the role is hoisted

## $isManaged\[roleid\] 

returns true or false. This checks if the role is managed . It will return true, if the role is managed

{% hint style="info" %}
What are managed Roles?  
Managed role are Roles from Bot which you cannot give a normal Member Aka. managed by integration 
{% endhint %}

## $isMentionable\[roleid\] 

returns true or false. This checks if the role is mentionable.That means that Member or bot can mention the role . It will return true, if the role is mentionable.

## $isMentioned\[userid/roleid/channelid\] 

returns true or false. This checks if the user/role/channel has been mentioned .It will return true, if it has been mentioned

## $isMuted\[userid\] 

returns true or false. This checks if the user is muted in a Voice channel.It will return true, if the user is muted

## $isNumber\[stringtocheck\] 

returns true or false. This checks if the parameter is a number like 10 is a Number and "hhkhk" is not a Number and would return false

## $isUserDMEnabled\[userid\] 

returns true or false. This checks if Dm of the User is Enabled

## $isValidHex\[hex-with-\#\] 

returns true or false. This checks if the string is a hex.Like \#abc is a valid Hex

## $isValidInvite\[invitecodeorlink\] 

returns true or false. This checks if the invite is valid will return yes if it is valid

## $isValidLink\[hex-with-\#\] 

returns true or false. This checks if the string is a valid link.Like https://ccommandbot.ga is a valid link and would return true

## $isValidObject\[Object\] 

returns true or false. This checks if the string is a Object

```text
$isValidObject[{"value":1}]
```

> **Output: true**

## $isEmoji**\[emoji\]**

**emoji =** &lt;:name:id&gt;

checks if the emoji exists and returns true or false.





