# Argument

Args are useful when you have custom commands where you have to enter a input

The command must include \| since it uses startswith

Example:

![example setup](../.gitbook/assets/image%20%2832%29.png)

Arguments are saved in a Array so $message\[1\] would output the first argument

![](../.gitbook/assets/image%20%2813%29.png)

Arguments get splited on whitespace !say hi hello.The first args would be hi the second hello.  
**In this way you can catch the User Input and use it for the custom command**  


### Args Functions

### $argsCheck\[&gt;&lt;number;error\(message\)\]

check if the number of args has been provided

`$argsCheck[>2;You did not provide 2 args]`  
If the user provided only 1 argument it will return the error and terminate the code

### $argsCount

returns the number of args the user provided

