# Trigger/Events

{% hint style="info" %}
**What is a trigger?**\
****The trigger starts an execution of a custom command. If it meets specific requirements it will trigger the command &#x20;
{% endhint %}

## All triggertypes/events&#x20;

* Message : triggers if a User sends a message&#x20;
* Reaction: triggers if a User reacts on a message
* Join/leave: triggers if a User joins or leaves your Server
* Interval: triggers on a provided interval
* Timed: triggers on a provided Time/Date
* Voice join/leave: triggers if a User joins/leaves a voice channel
* Button: triggers: if a User clicks a created Button from the Bot
* Role add/remove: If a User gets a Role added/removed ,it can trigger a custom command

The trigger are highly configurable. So you can select **Message** as triggertype and **!help** as trigger. Which would trigger the Custom Command, if a user uses **!help.**

## Message

message trigger supports

* Exact Match
* [Regex](https://www.sitepoint.com/learn-regex/)
* Starts with (you need a | after your trigger)

#### Regex

It would trigger, if the user sends hello

![execute it if the regex matches with it](<../.gitbook/assets/image (14).png>)

#### Exact Match

The Message must be same as the trigger&#x20;

![execute it if the msg is hello will not work if the message is hello Rake](<../.gitbook/assets/image (12).png>)

#### Starts with | Command

like for example for a kick command you need arguments .!kick @Rake .So @Rake would be the first argument&#x20;

![execute it if the message starts with hello](<../.gitbook/assets/image (23).png>)

**For more info:**&#x20;

{% content-ref url="argument.md" %}
[argument.md](argument.md)
{% endcontent-ref %}

{% hint style="info" %}
You can trigger on all message too by using %all% as trigger
{% endhint %}

## Reaction

The cc gets executed ,when a member reacts to a **message**. You can specify if it should trigger on reaction add / remove or on a specific message(You have to use the id for it)

![execute it if somebody adds the reaction 👍](<../.gitbook/assets/image (9).png>)

![execute it if somebody removes the reaction 👍](<../.gitbook/assets/image (37).png>)

![execute it if somebody add/remove the reaction 👍](<../.gitbook/assets/image (7).png>)

![execute it if .. a/r the reaction 👍 on the message with the given id](<../.gitbook/assets/image (33).png>)

There a possibility add,👍=8797908908088 too, which will only trigger on reaction add to the message with id 8797...

## Member add/leave

member trigger is useful, when you want to execute cc like for Example Welcome Message or Role add. Therefore you have to set the triggertype on Join/Leave. There are Options to execute cc only on join or leave. Just set the trigger **add** and it will only execute by Member join or **remove** for Member Leave. For Both: leave the field empty.

![This will execute ,when a member joins](<../.gitbook/assets/image (25).png>)

![This will execute,when a member leaves](<../.gitbook/assets/image (40).png>)

## Interval

Interval trigger is useful, when you want to execute cc every x minutes. Set the trigger type at Interval and set the time in minutes you want to execute the command(6 min minimum).\
**Pls check Interval/Timed for more info**

![](<../.gitbook/assets/image (55).png>)

{% hint style="warning" %}
Don't forget to set channelUsed, else the bot can't send any messages&#x20;
{% endhint %}

## Timed

Timed Event only get executed onetime after it execution you can let it delete itself by choosing delete as trigger. If the field is  empty the  Custom Command will not get deleted

![](<../.gitbook/assets/image (57).png>)

**Pls check Interval/Timed for more info**

{% hint style="warning" %}
Don't forget to set channelUsed, else the bot can send any messages&#x20;
{% endhint %}



## Voice join/leave

The cc gets executed when a user joins a voice channel or leaves it. You can set Trigger to:

* **join**  executes only if somebody joins a vc
* **leave**  executes only if somebody leaves a vc
* **empty** executes on both

![executes on voice join](<../.gitbook/assets/image (64).png>)

![executes on voice leave](<../.gitbook/assets/image (65).png>)

![executes on voice join and leave](<../.gitbook/assets/image (63).png>)

## Button

Button is like reaction Trigger. It is quite useful since it is highly customizable and you don't have to remove the reaction anymore&#x20;

Set the trigger as the **Button id** of the created Button.\
You can use multiple Buttons by splitting it with | like id|id2|id3 or by using regex

![executes when the button with the id = customid got clicked](<../.gitbook/assets/image (66).png>)

For creating Buttons pls check [Button functions](../custom-commands/button.md)

## Role add/remove

{% hint style="warning" %}
Role add/remove ,compares the old user with the new. That's why the user must be cached ,to check which role got added. To cache the Member: The Member have to execute a Custom Command like type of reaction, message and so on .&#x20;
{% endhint %}

When a Bot/Moderator adds a Role to a User it can trigger a Custom Command. This can be used for Server Boost tracking too or Configuration with other Bots.

![triggers on role add and remove](<../.gitbook/assets/image (68).png>)

The number is roleid ,It is still possible to use the rolename

![](<../.gitbook/assets/image (67).png>)

You can specify,if it should trigger on Role add or remove by adding `add,` or `remove,` before the role(id/name)

![](<../.gitbook/assets/image (71).png>)

![](<../.gitbook/assets/image (70).png>)

### Using role trigger for Server Boost tracking

1.Get the role id in Server Settings  and set as Trigger `add,roleid`

![](<../.gitbook/assets/image (69).png>)

