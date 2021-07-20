---
description: >-
  here you will find functions that you can't sort to category and use ful
  functions to
---

# Useful Functions

## $executionTime

returns the time the bot needed to execute the code

## $error

this function returns erro which are caused from the interpreter .If perms are missing or others\(Useful for debugging\)

## $suppressErrors\[error msg \(optional\)\]

this function binds all error and sends a custom one you choose

## $wait\[time\(s/m/h/d\)\]

this executes a delay and wait till it ends. The delay can stop if the bot crashes :c

## $creationDate\[userid/guildid/roleid;time/ms/date\]

this function returns the creationDate of the chosen id and in the format you choose

## $uri\[encode/decode;text\]

encodes/decodes a uri to pass a proper query for a search request Like 'Hello World' would be encoded 'Hello%20World'

## $forEach

Will loop over a list and every loop it will take an item and assign in inside varname accessible by $get\[varname\]

**Usage:** `$forEach[varname;LIST (ex: mido rake azz);Seperator (Optional, default is space)] SOME CODE HERE... $endForEach`

**Example:**

```bash
$forEach[name;mido rake azz blek felix] 
Hello $get[name] 
$endForEach 

Output: 
Hello mido 
Hello rake 
Hello azz 
Hello blek 
Hello felix
```

#### $seq\[Start;End;Step \(optional, default=1\)\]

Usage in $forEach

```bash
$forEach[num;$seq[0;5]]
 Number $num
$endForEach
```

## **$function**

Create a user-defined function that can be called by $callFunction or $functionName \(see !!func $callFunction\) **Note:** function name cant start with number, and must be within \[A-Z or a-z or \_ or 0-9\]

Usage

```text
$function[Function name;Param 1 (optional);Param 2...(optional)]
CODE...
$endFunction

Example Of Printing Hello To a user:
$function[printHello;user]
    Hello $user
$endFunction
$printHello[Rake]

Output: Hello Rake

Same Example but with $return:
$function[printHello;user]
    $return[Hello $user]
    [This message wont be returned]
$endFunction
$printHello[Rake]

Output: Hello Rake
```

\*\*\*\*

