# calculator
Calculator Project

This is just a basic calculator application.

Created Using
 -HTML
 -CSS
 -JavaScript


In order to make the calculator operational, I used a JavaScript. 
I used data-element to define the numbers, operands, and operations.
I used the querySelector to define the elements within JS and created variables for each button.

In order to get the calculator computing, I used a compute function.
I used an if statement and switch to define the operations.
I also used getDisplayNumber to properly display the operands, using toLocaleString('en').
This allowed the digits to display with commas.

I split the string into two parts in order to properly use the decimal.
I used the integerDigits to pass the numbers before the decimal place and decimalDigits to pass the numbers after the decimal place.
