---
description: with this functions you can save variable to db and get them
---

# db Functions

> List of Db set Functions  
> $setServerVar,$setChannelVar,$setMessageVar,$setUserVar

> List of Db get Functions  
> $getServerVar,$getChannelVar,$getMessageVar,$getUserVar

> List of Db delete Functions  
> $deleteServerVar,$deleteChannelVar,$deleteMessageVar,$deleteUserVar

{% hint style="success" %}
**$initVar\[server/message/channel/user;varname;Defaultvalue;id\(optional\)\]**

This function checks if the user variable exist .If not it will initialize a var with the default var

Example:

```text
$getUserVar[money;$sum[$getUserVar[money];1]]
//would throw a error since the user var does not exist.
// but if you have:
$initVar[user;money;0] 
//would initlaize a user var with 0
```
{% endhint %}

### $setServerVar\[Varname;Value\]

saves a variable to the db Varname and the Value is Value

### $getServerVar\[Varname\]

gets a variable from the db would output Value

### $setChannelVar\[Varname;Value;channelid\(optional\)\]

saves a Channel variable to the db Varname and the Value is Value

### $getChannelVar\[Varname;channelid\(optional\)\]

gets a variable from the db would output Value

### $setMessageVar\[Varname;Value;messageid\(optional\)\]

saves a Message variable to the db Varname and the Value is Value

### $getMessageVar\[Varname;messageid\]

gets a variable from the db would output Value

### $setUserVar\[Varname;Value;userid\(optional\)\]

saves a User variable to the db Varname and the Value is Value

### $getUserVar\[Varname;userid\(optional\)\]

gets a User from the db would output Value

### $userLeaderboard

generates a leaderboard for a variable, which you can sort

Usage:

```text
$userLeaderboard[variable;asc/desc (optional);{top} - {username}: {value};list (optional)]
```

{% hint style="info" %}
asc - greatest to least \(top to bottom\)

desc -  least to greatest \(bottom to top\)

{top} -  leaderboard position \(1./2./3./etc\)

{username} - username of User

{value} - value of the var
{% endhint %}

### $deleteChannelVar\[varname;chid\(optional\)\]

### $deleteServerVar\[varname\]

### $deleteUserVar\[varname;userid\(opt.\)\]

deletes the variable 

