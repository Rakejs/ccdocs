---
description: this is useful when you want to check conditions
---

# if functions

{% hint style="info" %}
Check only if for inline if statement
{% endhint %}

### Main Function

### $if

Is the start of a If function

```
$if[val1(!=/==/>=/<=/>/<)val2]
```

## Sub Functions

### $else

useful when you want to return a message if the condition is false.

### $endif

with this you are ending the if statement you can start a new. This is required

### $elseIf

make a second if with in a if statement

```
$elseIf[val1(!=/==/>=/<=/>/<)val2]
```

### $endelseIf

the end of a else if required!

### Example1:

```
$if[2==2]
2 is equal to 2!
$else
2 is not equal to 2
$endif
```

this would output every time 2 is equal ... .Since 2==2 is true.The else is just optional and not required for a if statement

### Example2:

```
$if[1==1]
1 is equal to 1!
$elseIf[2==2]
2 is equal to 2
$endelseIf
$endif
```

this would output every time 1 is equal ...a nd 2 is equal...As you can see it is like a if statement in a if.**It is possible to use multiple elseif statement**

{% hint style="warning" %}
Every Function is case sensitive so $if\[1== 1] would never return true since it includes a whitespace
{% endhint %}

### $checkCondition\[val1(!=/==/>=/<=/>/<)val2]

this will check the condition and return true/false

like `$checkCondition[hi==hi]` would return true

## Syntax

### Exact Match

`==` - Use this 2 signs to check if 2 values EXACTLY match eatch other.

`!=` - Use this 2 signs to check if 2 values do NOT match each other.

`&gt;=` - Use this 2 signs to check if number string 1 greater is, or the same as number string 2

`&lt;=` - Use this 2 signs to check if number string 1 is smaller, or the same as number string 2

`&gt;` - Use this sign to check if number string 1 is greater then number string 2

`&lt;` - Use this sign to check if number string 1 is smaller then number string 2

{% hint style="warning" %}
Please keep in mind, that if/ onlyIf statements use EXACT match! So if I would check\\: `$if\[ccommandbot.ga==Ccommandbot.ga\]` it will be false, because of the capital `C`
{% endhint %}
