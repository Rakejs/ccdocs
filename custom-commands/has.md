---
description: This functions returns a Boolean(true or false)
---

# has functions

## $hasEmbeds\[channelid,messageid\]    

returns true or false.If the message has embed it will return true if not then it will return false

## $hasRoles\[userID;roleID\] 

returns true or false.If the user has the role it will return true if not then it will return false for may roles use

**$hasRoles\[userid;roleid1;roleid2;..\]**

## $has**Any**Role\[userID\(optional\);roleID\] 

returns true or false.If the user has one of the role it will return true if not then it will return false for may roles use

**$hasRoles\[userid;roleid1;roleid2;..\]**

## $**has**Perms\[userid;perm1;perm2;.....\]

check if the user has Permission in the guild.You can add more then 2 perms. Check the permission list under Options

```text
$onlyBotPerms[admin;You are missing admin Permission]
Secret acess
```

If the user does not have admin Perms it will return false

## $**hasAny**Perm\[userid\(optional\);perm1;perm2;.....\]

check if the user has one of the Permission in the guild.You can add more then 2 perms. Check the permission list under Options

