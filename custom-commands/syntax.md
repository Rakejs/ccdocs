---
description: Read all of the syntax's used by the bot!
---

# Categories covered:

> Trigger Syntax + usefull regex's, $if/ $onlyIf syntax, Escaping characters, Encoded character codes

## Trigger Syntax's

### Word:

{% hint style="warning" %}
Please note:

The bot will only trigger commands, when it can see the channel! Make sure the bot has permissions to view the channel you use for the command. And make sure "Send Messages" is enabled!

Also, check out this page for settings that might be a problem for your commands! {% page-ref page="settings.md" %}
{% endhint %}

**Default syntax's, unique to our bot:**

"!test": It will trigger when !test is send in any channel the bot can see

"!test|: It will trigger when a message starts with "!test" \(you can use the other words as arguments: {% page-ref page="arguments.md" %}\)

"!test|i" It will trigger when a message starts with "!test" but capitalization doesn't matter


**REGEX syntax's:**

Comming soon! Stay tuned



### Reactions:

"&#x1F44D" Triggers when the reaction; &#x1F44D is added or removed

"add, &#x1F44D" Triggers when the reaction; &#x1F44D is added

"remove, &#x1F44D" Triggers when the reaction; &#x1F44D is removed

"add, &#x1F44D=MESSAGE ID" Triggers when &#x1F44D is added to the message with the specify messageID


{% hint style="info" %}
Check out {% page-ref page="trigger.md" %} to see all triggers that can be used!
{% endhint %}

## $if/ $onlyIf statements

`==` - Use this 2 signs to check if 2 values EXACTLY match eatch other.

`!=` - Use this 2 signs to check if 2 values do NOT match each other. 

`&gt;=` - Use this 2 signs to check if number string 1 greater is, or the same as number string 2

`&lt;=` - Use this 2 signs to check if number string 1 is smaller, or the same as number string 2

`>;` - Use this sign to check if number string 1 is greater then number string 2

`<;` - Use this sign to check if number string 1 is smaller then number string 2

## Escaping Characters

Because our bot uses characters like: `[]` and `$` as "prefix's" for code blocks, you need to escape them when used in a text, specified in the code

Use a `\` for that sort of stuff... Special characters are linked below

### Special Characters

```[, ], ;, :, $, >, <, =, {, }```

## Encoded Character Codes

```#RIGHT# =>> [
#LEFT# =>> ]
#SEMI# =>> ;
#COLON# =>> :
#CHAR# =>> $
#RIGHT_CLICK# =>> >
#LEFT_CLICK# =>> <
#EQUAL# =>> =
#RIGHT_BRACKET# =>> {
#LEFT_BRACKET# =>> }```
