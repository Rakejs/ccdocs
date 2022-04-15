# Interval/Timed

Interval and Timed Custom Commands are used for automated Execution

## Interval

* Interval can only get executed every 6min.
* The Period between other Interval must be longer then 3sec
* Every Interval Execution cost 0.005 voting Credits only applicable for non-premium server

## Timed

* The Last Execution must be 3sec behind, else it will not get executed

## Setting Interval and Timed

For every Interval and Timed a starting Time must get set, else the cc will never get executed. Therefore you have to set the Time, where the Bot should do the first Custom Command execution. From there the bot will do the next execution with the given period like every 6min

![Set The Time for Execution](<../.gitbook/assets/image (58).png>)

![Hit the Set Button](<../.gitbook/assets/image (56).png>)

{% hint style="warning" %}
For Interval a Value is required for the Time to the next execution. Example 6m,10y\
Time Format: number(m/h/d/w/y)\

{% endhint %}

![Value for Interval](<../.gitbook/assets/image (60).png>)

{% hint style="success" %}
Timed event allows you to select delete as trigger. Which will delete the custom command after execution


{% endhint %}

![delete as trigger](<../.gitbook/assets/image (61).png>)

## !!event Command

This command shows all running Interval and Timed Event or stopped due to the upper reasons

&#x20;

![](<../.gitbook/assets/image (59).png>)

### $setTimeout function

#### $setTimeout\[time (like 5s);name (optional);user id (optional)]

Example:&#x20;

```
$setTimeout[5m;remind;$authorID] 
Hello world! after 5m
$endTimeout
```

{% hint style="warning" %}
set Timeout creates a temporary Custom Command.So you need enough limit left
{% endhint %}
