---
description: watch our demo
---

# Begin

{% embed url="https://www.youtube.com/watch?v=vmVOn\_XeOes" %}

The Full Tutorial of Custom Command Bot

This is just a demo 😊

### Getting Started with Dashboard\(1\*Vote required\)

1. Go to[ https://ccommandbot.ga](%20https://ccommandbot.ga) 

![Login with Discord](../.gitbook/assets/image%20%2835%29.png)

![Go to Dashboard and select the Server](../.gitbook/assets/image%20%2826%29.png)

![Go to Custom Commands](../.gitbook/assets/image%20%2831%29.png)

![Create a File with the green Button](../.gitbook/assets/image%20%2827%29.png)

![edit the custom command](../.gitbook/assets/image%20%2820%29.png)

![set the type word,trigger hi and code hello](../.gitbook/assets/image%20%283%29.png)

![save the custom command](../.gitbook/assets/image%20%2818%29.png)

![send hi. The bot will send hello](../.gitbook/assets/image%20%2839%29.png)

### Getting Started using Commands

![send !!create and send yes to start setup](../.gitbook/assets/image.png)

![choose your type .This time we are using message](../.gitbook/assets/image%20%2834%29.png)

![Choose you trigger like hi, as response we have hello](../.gitbook/assets/image%20%2838%29.png)

![save the custom commands](../.gitbook/assets/image%20%2816%29.png)

![send hi and the bot should respond](../.gitbook/assets/image%20%2836%29.png)

## Code Syntax

The Syntax has been inspired from bdfd/dbd.js originally. The syntax so very similar and we try to keep error handling the same to have a really good ux. 

{% hint style="warning" %}
We are not affiliated with dbd.js/bdfd/bd-script. We just use their syntax  
btw **Functions gets executed Reversed** so think a little bit **upside-down**
{% endhint %}

### Syntax

**$**  -&gt; every Function starts with a usd  
**Functionname** --&gt; function name like sub,sum ..  
//only with functions with parameters  
**\[**-&gt;start of Parameter  
**value1**-&gt;your first Value  
**;** -&gt; Separator. This Separator separates the value  
**second value** .....separte every value with a ;  
**\]**end of Function  
  
**\*functions** are case sensitive.So `$addCmdReactions[ 🧨;  😉]` will not work since it has white space. So remove unnecessary white spaces,

The Functions return values or execute something. like $year would replace it with 2021

Example:

```text
The year Today is: $year
```

This would just replace $year and output The year Today is: 2021.

Example2:

```text
Hello my Name is <@$authorID>
```

This would just output : Hello my Name is Rake

Example3:

```text
$giveRoles[$auhtorID;roleid]
```

This would return nothing since it executes a functions. The Bot would give the role.

