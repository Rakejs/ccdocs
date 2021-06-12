---
description: >-
  this Functions does not return.If the functions returns false .It will throw a
  message you choose and stop the code.
---

# only Functions

> only Functions  
> $onlyBotPerms ,$onlyForCategories ,$onlyForChannels ,$onlyForIDs ,$onlyForRoles, $onlyIf $onlyIfMessageContains ,$onlyNSFW, $onlyPerms

## $onlyBotPerms\[perm1;perm2;.....;yourerrormessage\]

check if the bot has Permission in the guild.You can add more then 2 perms. Check the permission list under Options

```text
$onlyBotPerms[admin;You are missing admin Permission]
Secret acess
```

If the bot does not have admin Perms it will return "You are ...." and terminate the code.If it has the perms it  execute the full code.

## $onlyForCategories\[id1;id2;.....;yourerrormessage\]

check if the command gets executed in the category. You can add more then 2 categories.It will return the error message if it gets executed anywhere else

## $onlyForChannels\[id1;id2;.....;yourerrormessage\]

check if the command gets executed in the channel. You can add more then 2 channels.It will return the error message if it gets executed anywhere else.

## $onlyForIDs\[id1;id2;.....;yourerrormessage\]

check if the command gets executed by the user with the given id. You can add more then 2 ids.It will return the error message if it gets executed by somebody else

## $onlyForRoles\[id1;id2;.....;yourerrormessage\]

check if the command gets executed by a Member which has the role. You can add more then 2 roleids.It will return the error message if it gets executed from a Role which is not included

## $onlyIf\[value\(!=/==/&gt;=/&lt;=/&gt;/&lt;\)value2;yourerrormessage\]

check if the command  onlyif returns true.Else it would throw your error message and terminate the code

## $onlyIfMessageContains\[yourtext;word1;word2;..;yourerrormessage\]

check if the message contains the given text and contains the word.You can have more than 2 words by adding word3;word4 and ......If the Message does not contain the word it will throw your errormessage and terminate the code.

## $onlyIfMessageContains\[yourtext;word1;word2;..;yourerrormessage\]

check if the message contains the given text and contains the word.You can have more than 2 words by adding word3;word4 and ......If the Message does not contain the word it will throw your errormessage and terminate the code.

## $onlyForIDs\[id1;id2;.....;yourerrormessage\]

check if the command gets executed by the user with the given id. You can add more then 2 ids.It will return the error message if it gets executed by somebody else

## $onlyNSFW\[yourerrormessage\]

check if the command gets executed in a nsfw channel.Else it would throw the message and terminate the code

## $onlyPerms\[perm1;perm2;.....;yourerrormessage\]

check if the user has Permission in the guild.You can add more then 2 perms. Check the permission list under Options

```text
$onlyBotPerms[admin;You are missing admin Permission]
Secret acess
```

If the user does not have admin Perms it will return "You are ...." and terminate the code.If it has the perms it  execute the full code.



