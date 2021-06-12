# create Functions

### $createChannel\[name;text/voice;return id yes/no\(optional\);category id\(optional\)\]

creates a channel with name and type you choose like text would create a Text channel

#### $createRole\[name;color\(opt\);mentionable\(\);hoisted\(\);position\(\);perms1;perms2\]

creates a role with name. For Permission check the Permission list under Options

#### $createWebhook\[chid;name;avatar url;return id\(yes/no\);seperator\]

```text
$createWebhook[2433443433;name;https://imgur.com/test.png;yes;,]
```

creates a Webhook with given Value

### $createObject

creates a object,which you can use to add property

```javascript
$getObjectProperty[Rake]
$addObjectProperty[Rake;Fullstack Dev]
$createObject[{}]
```

this creates a Object and adds a Object Property to it getObject.. would return Fullstack Dev.

