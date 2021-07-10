# Button functions

### $button\[label;style/url;link/id;emoji\(optional\)\]

`$button[label;style/url;link/id;emoji(optional)]`

#### Example\(button\): 

`$button[B;green;id]`

**Example\(emoji\):**  
`$button[emoji;red;id;🚚]` `$button[emoji;red;id;$customEmoji[emojiname]]`

**Example\(link\):**   
`$button[B;url;`[`https://example.com`](https://example.com)`]`

Available Button Colors: _red, green, blurple, gray/grey_

_Do send a button the message needs a content for Example  
!!exec a_ `$button[B;url;https://example.com]`

## $addButton

Adding a button to a message

```text
$addButton[Message ID;Label;style/url;link/id;emoji(optional)] 
Available Button Colors: red, green, blurple, grey 
Example: 
$addButton[863xxxxxxxxxx21130;Visit example.com;url;https://example.com]
```

## $removeButton 

Remove a button from a message by \(label/emoji/url/id\)

**Usage:** `$removeButton[Message ID;Label/Emoji/URL/ID (optional, empty means removing the last button)]`

 **Example \(Remove Button by label\):**`$removeButton[863xxxxxxxxxx21130;Visit example.com] Example (Remove Last button): $removeButton[863xxxxxxxxxx21130]`

