---
layout: project
category: ch4-fundamental-data-types
title: Ch4 Modulus Clock
---
Create a program that uses integer division and modulus division to calculate the time after a specified number of hours and minutes.

Review the example on Big Java pg 138 about converting pennies to dollars using / and %.

  - DO NOT worry about am or pm

  - DO NOT use any [magic numbers]

  - You MUST start by writing your pseudocode as comments.

1.  Prompt the user for the hour of the start time.
1.  Prompt for the minutes of the start time.
1.  Prompt for the number of hours later
1.  Prompt for the number of minutes later.
1.  Calculate the future time.
1.  Include a conditional statement like the one below at the end of your calculation so that 0 o'clock becomes 12 o'clock (you do NOT need to use the variable name futureHour)
1.  USE PRINTF to display the current time and the future time will be after that many hours and minutes. For example...
```
Current time:     2:09
Future time:      5:09
```


Example conditional statement so that 0 o'clock becomes 12 o'clock (you do NOT need to use the variable name futureHour)
```
// Convert zero o'clock to twelve o'clock
if (futureHour == 0){
  futureHour = 12;
}
```


[magic numbers]: https://en.wikipedia.org/wiki/Magic_number_(programming)#Unnamed_numerical_constants
