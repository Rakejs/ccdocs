---
description: functions for creating Embeds
---

# Embeds

{% hint style="info" %}
to add a hyper link in embed use \[name\]\(link\)  
Example $description\[the \[Name\\]\([https://discord.com/](https://discord.com/)\) is\]  
the \ is needed
{% endhint %}

### $author\[Name;url\]

sets author 

### $title\[Title;Url\(optional\)\]

sets the title and sets Url if you provided one

### $description\[descripition\]

sets the description

### $color\[hex\]

set a color with a hex or use RANDOM for a random color

### $thumbnail\[url\]

sets the thumbnail

### $image\[url\]

sets the image

### $addField\[title;value;inline  yes/no \(optional\)\]

adds a Field.For Inline user yes as third param.For a second Field use the function again

### $footer\[footertext,url\]

sets the footertext and a url if provided

### $addTimestamp\[time in ms\] or $addTimestamp

sets the Timestamp for the given time in ms or the current Timestamp

### Example:

```bash
$author[Rake]
$title[Title]
$description[descripition]
$color[RANDOM]
$thumbnail[https://images.png]
$addField[title;value;no]
$addField[title;value;yes]
$addField[title;value;yes]
$image[https://images.png]
$footer[footertext]
$addTimestamp
```

![Rake testing Embed command](../.gitbook/assets/image%20%285%29.png)

## Extra

It is not possible to send embeds in channel or send Message or editMessage\(works with every function where you send message\).Therefore you must use this Structure:

```bash
{title:text}
{url:link}
{footer:text:url}
{description:text}
{color:hex}
{author:text:url}
{thumbnail:url}
{field:name:value:inline}
{timestamp:ms}
{image:url}
{reactions:emoji,emoji2,...}
{suppress:yes/no}
{delete:time}
{attachment:name.extension:url}
{deletecommand:time}
```

### Example:

old message hi  
code: `$editMessage[773696146089967688;{title:bye}]` would edit the embed.

![](../.gitbook/assets/image%20%2830%29.png)

