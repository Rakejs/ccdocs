---
description: this functions filters our data
---

# Find functions

### $findChars\[string\]

this functions filters out the character from the string

```text
$findChars[f2bj23jk34jbjb43jk43]
```

> **Output**: fbjjkjbjbjk

### $findNumbers\[string\]

this functions filters out the number from string

```text
$findNumbers[f2bj23jk34jbjb43jk43]
```

> **Output**: 223344343

### $findSpecialChars\[string\]

this functions filters out special Chars like !,",$,§...

```text
$findSpecialChars[!"s§s$s%d&d/(s]
```

> **Output**: !"§$%&/\(

### $findTextSplitIndex\[number\]

this functions filters out special Chars like !,",$,§...

```text
$findTextSplitIndex[i]
$textSplit[s/i/a/c/g;/]
```

> **Output**: would return 2

### $findServerChannel\[id/mention/name;yes/no \(optional\)\]

search the channel in the server and returns it. If you have yes selected as parameter it will return a channelid . Else it will return undefinded 

### $findRole\[id/name/mention\]

returns the roleid from the given parameter

### $findMember\[name/mention/id;yes/no \(optional\)\]

returns the userid from the given parameter.If no Member was found it will return the authorID







