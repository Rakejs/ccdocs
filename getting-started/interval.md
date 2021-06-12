---
description: not released yet
---

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

![Set The Time for Execution](../.gitbook/assets/image%20%2858%29.png)

![Hit the Set Button](../.gitbook/assets/image%20%2856%29.png)

{% hint style="warning" %}
For Interval a Value is required for the Time to the next execution. Example 6m,10y  
Time Format: number\(m/h/d/w/y\)  
{% endhint %}

![Value for Interval](../.gitbook/assets/image%20%2860%29.png)

{% hint style="success" %}
Timed event allows you to select delete as trigger. Which will delete the custom command after execution
{% endhint %}

![delete as trigger](../.gitbook/assets/image%20%2861%29.png)

## !!event Command

This command shows all running Interval and Timed Event or stopped due to the upper reasons

 

![](../.gitbook/assets/image%20%2859%29.png)



