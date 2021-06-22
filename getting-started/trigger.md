# Trigger/Events

{% hint style="info" %}
**What is a trigger?**  
The trigger starts an execution of a custom command. If it meets specific requirements it will trigger the command  
{% endhint %}

## All triggertypes/events in overview

* Message : triggers if a User sends a message 
* Reaction: triggers if a User reacts on a message
* Join/leave: triggers if a User joins or leaves your Server
* Interval: triggers on a provided interval
* Timed: triggers on a provided Time/Date
* Voice join/leave: triggers if a User joins/leaves a voice channel

The trigger are highly configurable.So you can select **Message** as triggertype and **!help** as trigger. Which would trigger the Custom Command,if a user uses **!help.**

## Message

There are different type of trigger you can set like with regex,exaxt match or if it starts with.  


#### Regex

pls learn how to use regex [https://regexr.com/](https://regexr.com/)

![execute it if the regex matches with it](../.gitbook/assets/image%20%2814%29.png)

#### Exact Match

When the message content == trigger it will execute the code

![execute it if the msg is hello will not work if the message is hello Rake](../.gitbook/assets/image%20%2812%29.png)

#### Command

this is useful when you want to use Arguments.There for just add a `|` to your trigger afterwards.

![execute it if the message starts with hello](../.gitbook/assets/image%20%2823%29.png)

pls check Arguments for more info!



#### Trigger all Message

the bot will trigger to all message. Therefore add in the trigger **%all%**

## Interval

Interval trigger is useful, when you want to execute cc every x minutes. Set the trigger type at Interval and set the time in minutes you want to execute the command\(6 min minimum\).  
**Pls check Interval/Timed for more info**

![](../.gitbook/assets/image%20%2855%29.png)

{% hint style="warning" %}
Don't forget to set channelUsed, else the bot can send any messages 
{% endhint %}

## Timed

Timed Event only get executed onetime after it execution you can let it delete itself by choosing delete as trigger. If the field is  empty the  Custom Command will not get deleted

![](../.gitbook/assets/image%20%2857%29.png)

**Pls check Interval/Timed for more info**

{% hint style="warning" %}
Don't forget to set channelUsed, else the bot can send any messages 
{% endhint %}

## Member add/leave

member trigger is useful, when you want to execute cc like Welcome Message or Role add. Therefore you have to set the triggertype on Join/Leave. There are Options to execute cc only on join or leave. Just set the trigger add and it will only execute by Member join or remove for Member Leave. For Both: leave the field empty.

![This will execute ,when a member joins](../.gitbook/assets/image%20%2825%29.png)

![This will execute,when a member leaves](../.gitbook/assets/image%20%2840%29.png)

## Reaction

The cc gets executed ,when a member reacts to a Message. There different types like Reaction add /remove or both or on a specific message id 

![execute it if somebody adds the reaction &#x1F44D;](../.gitbook/assets/image%20%289%29.png)

![execute it if somebody removes the reaction &#x1F44D;](../.gitbook/assets/image%20%2837%29.png)

![execute it if somebody add/remove the reaction &#x1F44D;](../.gitbook/assets/image%20%287%29.png)

![execute it if .. a/r the reaction &#x1F44D; on the message with the given id](../.gitbook/assets/image%20%2833%29.png)

There a possibility add,👍=8797908908088 to. 

## Voice join/leave

The cc gets executed when a user joins a voice channel or leaves it. You can limit it too join and leave or bot

![executes on voice join](../.gitbook/assets/image%20%2864%29.png)

![executes on voice leave](../.gitbook/assets/image%20%2865%29.png)

![executes on voice join and leave](../.gitbook/assets/image%20%2863%29.png)



