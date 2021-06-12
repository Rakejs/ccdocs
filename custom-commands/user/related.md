---
description: 'related functions like kick,ban ..'
---

# related Functions

### $kick\[userid;reason\]

kicks the user with the given id

### $ban\[userid;reason;days\]

ban the user with the given id for x days default 0

### $unban\[userid;reason\]

unbans the user with the given id

### $cooldown\[time\(s/m/h/d/y\);erromessage if cooldown \]

set a cooldown for the current user. %time% returns the time left 

### $userRoleColor\[userid\] or $userRolecolor

returns the hex color of the Users highest Role

### $roleMembersCount\[roleid\]

returns the amount of the User which has the role\(Only cached Users\)

#### $usersTyping\[chid;name/mention/tag;separator \(optional\)\]

returns the user who are typing in the Channel with the given id in the format you choose \(name/tag/mention\)

### $boostingSince or $boostingSince\[userID;ms/date \(optional\)\]

returns the date/ms the user started to boost the Server.

### $userReacted\[chid\(optional\);messageID;userID;emoji\]

returns true/false true if the user has reacted on the message with the given id in the channel\(default:channelUsed\) 

