---
description: really important page please read it ,else you would face to problems
---

# Begin

#### If you didn't create your first Command, follow this:

{% content-ref url="create.md" %}
[create.md](create.md)
{% endcontent-ref %}

## Code Syntax

The Syntax has been inspired from BDFD originally.

{% hint style="warning" %}
We are not affiliated with BDFD. We just use their syntax
{% endhint %}

### Syntax

Functions returns Value or execute something.\
There are two type of functions:

* Functions with parameter ($giveRoles\[$authorID;080887889])
* Functions without parameter($channelID)

{% hint style="info" %}
**What is a parameter?**\
Parameters are Value ,which a Function needs. To understand it let us see the usage of **$giveRoles\[authorid;roleid]**\
1.Parameter is authorID. The authorID is the id of a User.To get the authorid we will use another function named **$authorID**, which returns the id of the executor

2.Parameter is the roleid.To get the roleid,you can copy the id of the role you want to give or use an anither function named **$roleID\[rolename]**
{% endhint %}

* Every Function starts with a **$**
* After it the function name comes like **giveroles**
* If the Function needs parameters you open it with **\[** **]**&#x20;
* Every Parameter gets separated with **;**&#x20;

So your result would be **$giveRoles\[authorid;roleid]**

{% hint style="info" %}
**Functions with many Parameters!**\
Did you know that some functions can have more then provided parameters for example **$randomText\[text1;text2]**\
You can add more then 2 text just split them up with ;\
like **$randomText\[text1;text2;text3;text4]** and so on _\*\*_
{% endhint %}

{% hint style="info" %}
**Function names are case insensitive !**\
That's why $authorID and $authorid would return the same result.
{% endhint %}

#### Example:

```
The year Today is: $year
```

This would just replace $year and output The year Today is: 2021.

#### Example2:

```
Hello my Name is <@$authorID>
```

This would just output : Hello my Name is <@rake>

#### Example3:

```
$giveRoles[$auhtorID;333333333]
```

This would return nothing since it executes a functions. The Bot would give the role to the Executor.

#### Example: Multiplie line code

```
$let[bal;0]
Current bal: $bal
$let[bal;10]
After change: $bal
```

Output: Current bal: 0 After change:10 The code shows that it gets executed from top to bottom. The function $let defines a temp var ,which you retrive with $bal
