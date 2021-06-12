---
description: Pls check how to use functions in the docs
---

# Random functions

This functions return an random number id/mention/channelid and more

## $random\[numstart;numend;yes/no\(optional default:no\)\]

this function returns a random number set the number border like from 0 to 10.The yes parameter returns a decimal and not integer

```text
1.Number: $random[1;10]
2.Number: $random[1;10;no]
3.Number: $random[1;10;yes]
```

> **Output**:1.Number: 1   
>               2.Number: 2   
>               3.Number: 9.849555985149912

## $randomChannelID

This functions returns a random channel id in your guild

## $randomMention

This functions returns a mentions a random person in your guild

## $randomRoleID

This functions returns a random role id

## $randomUserID

This functions returns a random userid

## Example

```text
$randomUserID userid
$randomRoleID roleid
$randomMention mention
$randomChannelID channelid
```

> **Output:** 717090829310886079 userid  
>                772053356378062889 roleid  
>                @Da Beast mention  
>                772051119923789847 channelid

## $randomText\[text1;text2\]

this function returns a random text from your value you can have more then one value by adding your next Text with a ; like $randomText\[hi;hello;hey;Bonjour\]

```text
$randomText[hi;hello;hey;Bonjour]
```

> **Output:  hi**

## $randomString\[length\]

this function returns a random string in your length you choose like this a random string "vnTaa9lG"

```text
Cat is Typing: $randomString[10]
```

> **Output:**  Cat is Typing: JRtccrZnJY



