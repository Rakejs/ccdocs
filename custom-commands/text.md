---
description: with this function you can change data split them and more
---

# Text Functions

> List of text functions  
> $charCount $checkContains  $joinSplitText $numberSeparator $removeSplitTextElement $replaceText $replaceTextWithRegex $splitText $stringStartsWith $textSplit $toLocaleUppercase $toLowercase $toUppercase, $advancedTextSplit,$commandCode, $editTextSplitElement,$repeatmessage,$removeTextSplitElement,$spliceTextJoin,$stringEndsWith ,$textSplitMap

### $charCount\[text\]

returns the number of characters in a text

### $checkContains\[text;tocheck1;tocheck2\]

returns true if text contains one of it.Else it will return false

### $joinSplitText\[separator\]

joins a spilt Text with the new separator

### $numberSeparator\[number;separator\(optional\)\]

separates the number with thousand digit like \[1000;,\] would return 1,000

### $removeSplitTextElement\[index1;index2\]

removes value from the given index

### $replaceText\[text;valueyouwantotreplace;new\]

replaces the value you want to replace in text with the new value  
like `$replaceText[Hello my name is Rake;hello;hi]`  
Output would be Hi my name is Rake since hello got replaced with hi

### $replaceTextWithRegex\[text;regex;flags;new\]

replaces the value with regex /flags you want to replace in text with the new value  
like `$replaceText[Hello my name is Rake;hello;g;hi]`  
Output would be Hi my name is Rake since hello got replaced with hi  
The g means global check  [regex flags](https://www.w3schools.com/jsref/jsref_obj_regexp.asp) for more info

###  $splitText\[index\]

is the value of the given index

### $textSplit\[text;separator\]

separates the text with the given separator

### Example

```text
$splitText[2] // = bye
$splitText[1] // = hello
$textSplit[hello/bye;/]
```

```javascript
$removeSplitTextElement[1;2]
$textSplit[hello/bye/hi;/]
//would remove hello and bye
```

```javascript
$joinSplitText[+]
$textSplit[hi-bye-hello;-]
//splits text and joins it with |
//Output:hi+bye+hello 
```

### $toLocaleUppercase\[text\]

this functions uppercase every first character from a word  
like `$toLocaleUppercase[hello how are you?]` would output:  
Hello How Are You?

### $toLowercase\[text\]

this functions lowercases every  character   
like `$toLowercase[RAKE]` would output: rake

### $toUppercase\[text\]

this functions uppercase every  character   
like `$toUppercase[hello]` would output: HELLO

### $advancedTextSplit\[text;split1;index1;split2;index2\]

this functions allows you to have more then one text splits  
**⚠ Only for advanced Users,else your brain** 🤯

```javascript
$advancedTextSplt[hello/bye|ok;/;2;|;1]
// would return bye|ok and the first index
//⚠ code is underwork
```

### $commandCode

outputs the code you have coded on the dashboard

### $editTextSplitElement\[index;word\]

edits the value with the given index

### $repeatMessage\[times;text\]

repeats the message with the given times

### $removeTextSplitElement\[index\]

removes the splitted Text from $textspilt with the given Index

### $concatTextSplit\[text;separator\]

adds a element to existing textsplit

### $spliceTextJoin\[text;sep1;sep2,every\(opt\)\]

joins the splitted text

### $stringEndsWith\[text;word\]

return true or false. If the text ends with the given word

### $textTrim\[text\]

remove useless space from the text like

`hello       bye` would return **`hello bye`**

### **$textSlice\[text;x;y\(optional\)\]**

slices the text from x to end or y if given.

### $cropText\[text;limit;charToSplit \(opt.\);append \(opt.\)\]

crops the text to the limit

### $indexOf\[text;char\]

returns the position of a char in the text.Default is 0

### $filterMessageWords\[text;casesensitive \(yes/no\);...words\]

removes words from a text



\*\*\*\*

\*\*\*\*







