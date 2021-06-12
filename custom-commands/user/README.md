---
description: 'this functions returns value like id or data, check related for more info'
---

# User\(member\) functions

> User functions:  
> $userAvatar ,$userExists, $userID, $username ,$userPerms, $userRoles, $usersBanned ,$usersInChannel ,$usersWithRole, $userTag,$memberJoinedDate,$membersCount,$authorID,$changeNickname,$botCount,$botTyping,$discriminator,$username,$nickname,$authorAvatar

{% hint style="danger" %}
Some of the functions requires caching.This means if you want to get data of a user ,which is not in the cache.like the user who used the command is in the cache.  
Therefore you have to use: **$cacheMember\[userid\]  
This is only required if you retrieve value not for roles add or kick or ban**
{% endhint %}

## $userAvatar\[userID;size\(optional\);dynamic\(optional\)\] or $userAvatar

returns the user Avatar from the given id or the author

## $userExists\[userID\]

returns a Boolean true/false.If the user exits it would be true

## $userID\[username\]

returns the userid of the user with name

## $userPerms\[userid\] or $userPerms

returns all permission of the given id or the author

![Rake testing User Perms command](../../.gitbook/assets/image%20%281%29.png)

## $userRoles\[userid;ids/mentions/name;\(optional\);seperator\(optional\)\]

## or $userRoles

returns the roles of the User in the format way choose like if you want to mention the Role,you will have to choose mentions.The default seperator is , you can change it too. $userRoles only gives the role of the User

## $userBanned\[userid\]

returns Boolean true/false.True if the user is banned.

## $usersInChannel\[channelID;id/username/mention\(optional\);separator \(optional\)\]

returns which Users are in Channel.Like $userRoles you can choose which value it should return and separator too

## $usersWithRole\[roleid;separator \(optional\)\]

returns which Userswith the given roleid.Like $userRoles you can choose the separator too.

## $userTag\[userid\] or $userTag

returns the tag of the user with the given id or the author

## $memberJoinedDate\[userid;date/time\(optional\)\] or $memberJoinedDate

returns the date the member Joined in date or time or from the current Author

![Output of time](../../.gitbook/assets/image%20%288%29.png)

## $membersCount

return the number of members in the guild

## $authorID

returns the author id

## $changeNickname\[userid\(optional\);nickname\]

changes the nickname of a User with the given id or the author when none provided

## $botCount

returns the number of Bots in the server

## $botTyping

the bot types in the channel for 2 seconds

## $discriminator

returns the user discriminator like 6882

## $username\[userid\] or $username

returns the username with the given id or the current user

## $nickname\[userid\] or $nickname

returns the nickname with the given id or the current user in the guild

## $authorAvatar

returns the author Avatar

## $status\[userid\]

returns the presence of the user.Works only for Custom Bot invisible,dnd,online,offline

