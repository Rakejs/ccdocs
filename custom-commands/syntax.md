---
description: Read all of the syntax's used by the bot!
---

# Syntax

## Categories covered:

> Trigger Syntax + usefull regex's, $if/ $onlyIf syntax, Escaping characters, Encoded character codes

### Trigger Syntax's

#### Word:

{% hint style="warning" %}
Please note:

The bot will only trigger commands, when it can see the channel! Make sure the bot has permissions to view the channel you use for the command. And make sure "Send Messages" is enabled!

Also, check out the page below for settings that might be a problem for your commands!
{% endhint %}

**Default syntax's, unique to our bot:**

"!test": It will trigger when !test is send in any channel the bot can see

"!test|: It will trigger when a message starts with "!test" (you can use the other words as arguments:

)

"!test|i" It will trigger when a message starts with "!test" but capitalization doesn't matter

**REGEX syntax's:**

{% hint style="warning" %}
REGEX is for advanced users only! Or you need to already know REGEX. For more info about it, please join our support server and ask for it.

We higly suggest, you learn REGEX yourself if you want to use it for all your commands!
{% endhint %}

REGEX to trigger a command with multiple prefixes

``/(^)(PREFIXES, SPLITTED WITH `|`)YOUR TRIGGER HERE/gi``

Check if a message contain (a) specfic word(s)

`/(^|\s)(WORD 1|WORD 2|WORD 3|enz...)/gi`

#### Reactions:

"👍" Triggers when the reaction; 👍 is added or removed

"add, 👍" Triggers when the reaction; 👍 is added

"remove, 👍" Triggers when the reaction; 👍 is removed

"add, 👍=MESSAGE ID" Triggers when 👍 is added to the message with the specify messageID

{% hint style="info" %}
Check out the trigger info page to see all triggers that can be used!
{% endhint %}

### $if/ $onlyIf statements

`==` - Use this 2 signs to check if 2 values EXACTLY match eatch other.

`!=` - Use this 2 signs to check if 2 values do NOT match each other.

`>=` - Use this 2 signs to check if number string 1 greater is, or the same as number string 2

`<=` - Use this 2 signs to check if number string 1 is smaller, or the same as number string 2

`>` - Use this sign to check if number string 1 is greater then number string 2

`<` - Use this sign to check if number string 1 is smaller then number string 2

### Escaping Characters

Because our bot uses characters like: `[]` and `$` as "prefix's" for code blocks, you need to escape them when used in a text, specified in the code

Use a `\` for that sort of stuff... Special characters are linked below

#### Special Characters

`[, ], ;, :, $, >, <, =, {, }`

### Encoded Character Codes

\`\`\`#RIGHT# =>> \[

## LEFT# =>> ]

## SEMI# =>> ;

## COLON# =>> :

## CHAR# =>> $

## RIGHT\_CLICK# =>> >

## LEFT\_CLICK# =>> <

## EQUAL# =>> =

## RIGHT\_BRACKET# =>> {

## LEFT\_BRACKET# =>> }\`\`\`
