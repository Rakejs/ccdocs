---
description: here you can find Functions like slowmode and more
---

# related Functions

### $slowmode\[channelid;time\]

sets the slowmode for a Channel like your time can be 1s or 5m max 6h.

### $cloneChannel\[channelid\] or $cloneChannel

clones the channel with the given id or the channelUsed

### $channelCooldown\[time;error message\]

sets a Cooldown for the channel

Cooldown does not have any limit   
Time format: number/s/m/h/d/w/y

```javascript
$channelCooldown[30s;%time% remains]
//if cooldown it would return the time remains
```

### $editChannel

detailed Description: 9 parameter.For not changing a value use **$default**

1. Channel ID \(required\)
2. New category ID \(ID/$default\)
3. New name \(Text/$default\)
4. New position \(Number/$default\)
5. NSFW \(\(yes/no\)/$default\)
6. Bitrate \(Number/$default\) \(Only for voiceChannels\)
7. Users limit \(Number/$default\) \(Only for voiceChannels\)
8. Sync category permissions \(yes/no\) \(Required\)
9. Reason \(Optional\)

like 

`$editChannel[chid;catid/$default;name/$default;position/$default;nsfw/$default (yes/no);bitrate/$default;userLimit/$default;syncPermission (yes/no);reason (optional)]`

### $useChannel\[channelid\]

sets the new channel Used. Bot will send all Message from there

##  $moveUser & $muteUser

Description:  
Move an user from a voice channel or disconnect them if optional params are not provided  
Mutes a user in the voice channel

Usage

```text
$moveUser[userID;channelID (optional);reason (optional)]
```

`$muteUser[userID;mute (yes/no);reason (optional)]`

