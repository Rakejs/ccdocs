# Date functions

{% hint style="warning" %}
### this functions return Time from the System
{% endhint %}

## $year

This function returns the current year.

```text
year: $year
```

> **Output**: year: 2021

## $month

This function returns the current month.

```text
month: $month
```

> **Output**: month: 3

## $day or $day\[yes/no\]

This function returns the current day or The day of the current week, if you choose yes.

```text
day: $day
day: $day[yes]
```

> **Output**: day: 14  
> day: Sunday

## $hour

This function returns the current hour.

```text
hour: $hour
```

> **Output**: hour: 3

## $minute

This function returns the current minute.

```text
$minute m
```

> **Output**:28 m

## $second

This function returns the current second.

```text
$second s
```

> **Output**:20 s

## $dateStamp

This function returns the number of milliseconds elapsed since January 1, 1970 00:00:00 UTC.

```text
$dateStamp
```

> **Output**:1613076007191

## $parseDate\[time in ms\(aka Date.now\);time/date\]

This function returns the date from the given ms in `Time` or `Date` format.

```c
Time :$parseDate[1613076007191;time]
Date :$parseDate[1613076007191;date]
```

> **Output**: Time :55 years 6 months 3 weeks 20 hours 40 minutes and 7 seconds  
> Date :Thu Feb 11 2021 21:40:07 GMT+0100 \(Central European Standard Time\)

## Example

This code returns a normal Time like 10.4.1987

```text
$day.$month.$year
```

> **Output**:11.2.2021

## $timezone\[Country/city\]

This function sets the Timezone for all date functions.

### $formatDate\[time;format \(optional\)\]

Formats the date.

#### Time Options:

* datestamp - Example: 1615578797890890
* ms - Example: 315569267878790ms
* string date - Example: 1/17/2021, 9:09:19 PM
* String in ISO - Example: 2000-3-12T14:48:00.000Z

#### Format Options:

* Blank \(default\) - Example: Sunday, 14 March 2021
* LT - Time - Example: 6:01 AM
* LTS - Time w/ seconds - Example: 1:58:3 AM
* L - Date - Example: 1/10/2021
* LLL - Specified Date - Example: March 12 2020 4:02 AM
* LLLL - - Specified Date w/ Day - Example: Friday, March 12 2021 4:02 AM
* dddd - Day - Example: Friday
* HH - Hour - Example: 15
* **Check here for more formats**

```javascript
$formatDate[$dateStamp] //Friday, March 14 2020
$formatDate[$dateStamp;LLLL] //Friday, March 14 2020 1:00 PM
$formatDate[$dateStamp;dddd at hour HH] //Sunday at hour 10
```

### $humanizeMS\[ms;limit \(optional\);separator \(optional\)\]

Converts ms to an easy to understand time.

```javascript
$humanizeMS[73789790129310] //64 years and 4 months
$humanizeMS[73789790129310;4] //64 years 4 months 22 days and 12 hours
$humanizeMS[73789790129310;4;,] //64 years, 4 months, 22 days, and 12 hours
```

