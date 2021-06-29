# create Functions

## $createChannel\[name;text/voice;return id yes/no\(optional\);category id\(optional\)\]

Creates a channel with name and type you choose. Like `text` would create a Text Channel.

### $createRole\[name;color\(opt\);mentionable\(\);hoisted\(\);position\(\);perms1;perms2\]

Creates a role with the name of your choice. For permissions, check the Permission list under Options.

### $createWebhook\[chid;name;avatar url;return id\(yes/no\);seperator\]

```text
$createWebhook[2433443433;name;https://imgur.com/test.png;yes;,]
```

Creates a webhook with given values.

## $createObject

Creates an object, which you can use to add properties.

```javascript
$getObjectProperty[Rake]
$addObjectProperty[Rake;Fullstack Dev]
$createObject[{}]
```

This creates an Object and adds a Object Property to it. `getObject` would return `Fullstack Dev`.

