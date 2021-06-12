---
description: Pls check how to use functions in the docs
---

# Math functions

This function calculates it and return is  
Function Structure `$name[num;num2]`

{% hint style="info" %}
### It is even possible to add more than 2 numbers by adding another number with a separator

### example: $sum\[1;2;3\]     //Output:6

### You can have nested Calculation too

### example: $sum\[$sum\[2;1\];2\]   //Output:7
{% endhint %}

## $math\[expression\]

calculates inside it

```javascript
$math[2+2] //4
$math[(2+2)*4] //16
/*
+ = Addition
- = Subtraction
/ = Division
* = Multi
() = Parathenses for equations inside
*/
```

## $sum\[num;num2\]

this function calculates the sum 

```text
Sum: $sum[2000;21]
```

> **Output**: Sum: 2021

## $sub\[num;num2\]

this function calculates the difference like 10-4=6

```text
Sub: $sub[10;4]
```

> **Output**: Sub: 6

## $multi\[num;num2\]

this function multiplies the value

```text
Multiply: $multi[10;4]
```

> **Output**: Multiply: 40

## $divide\[num;num2\]

this function divides the value

```text
Divide: $divide[10;4]
```

> **Output**: Divide: 2.5

## $modulo\[num;num2\]

this function calc. with % 10%4 =2

```text
Modulo: $modulo[10;4]
```

> **Output**: Modulo: 2

## Rounding Numbers

this function allows you to round Number

## $round\[num\]

this function rounds the number with Math.round\(\)

```text
Round: $round[3.1415926535]
```

> **Output**: Round: 3

## $roundTenth\[num;to \(optional\)\]

this function rounds the number with .toFixed

```text
Round: $round[3.1415926535;5]
```

> **Output**: Round: 3.1416

## $truncate\[number\]

this function remove the decimal

```text
Truncate: $truncate[6382638.7897908908]
```

> **Output**: Truncate: 6382638

## $abbreviate\[number\]

this function abbreviates large numbers

Abbreviation to:  
k - thousands  
m - millions  
b - billions  
t - trillions

```text
abbreviate: $abbreviate[6000]
```

> **Output**: abbreviate: 6k



## $ordinal\[number\]

adds the correct suffix after the number  
`st`,`nd`,`rd`,`th`

Like 2nd or 3rd ..

```text
ordinal: $ordinal[2]
```

> **Output**: abbreviate: 2nd

