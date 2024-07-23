# JS-cheatsheet

## Including JavaScript in an HTML-Page:

```
<script type="text/javascript">
  // JS code gose here
</script>
```
## Call an External JavaScript file:

```
<script src="myScript.js"></script>
```
## Comments:

Single line comments : ``` // only single line comments ```

Multi-line comments : ``` /* comment here */ ```

## Variables in JavaScript:

``` var : common variable, scoped to functions. ```

``` const : Immutable variable. ```

``` let : Mutable variable. ```

## Data Types 

Type | Example
-------- |  --------
Numbers   | var age = 23;
Variables  | Var = x;
Text (strings) | var name = "John";
Operations | var x = 5 + 2 + 3;
True/False statements | var x =  true;
Constant numbers | const PI = 3.14159;
Objects | var person = {firstName:"John", lastName:"Doe"};


## Objects:

```
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```
## Array Methods:
  
 syntax | Example
  -------- |  --------
  concat() | Combines arrays.
  indexOf() | Finds the index of an element in an array.
  join() | Joins all elements of an array into a string.
  lastIndexOf() | Returns the last index of an element in an array.
  pop() | Removes the last element of an array, and returns that element.
  push() | Adds new elements to the end of an array, and returns the new length.
  reverse() | Reverses the order of the elements in an array.
  shift() | Removes the first element of an array, and returns that element.
  slice() | Selects a part of an array, and returns the new array.
  sort() | Sorts the elements of an array.
  splice() | Adds/Removes elements from an array.
  toString() | Converts an array to a string, and returns the result.
  unshift() | Adds new elements to the beginning of an array, and returns the new length.
  valueOf() | Returns the primitive value of an array.

## Basic Operators:

Operator | Description
-------- |  --------
'+' | Addition
'-' | Subtraction
'*' | Multiplication
'/' | Division
'%' | Modulus
'++' | Increment
'--' | Decrement
'(...)'| Grouping

## Comparison Operators:

Operator | Description
-------- |  --------
'==' | Equal to
'===' | Equal value and equal type
'!=' | Not equal
'!==' | Not equal value or not equal type
'>' | Greater than
'<' | Less than
'>=' | Greater than or equal to
'<=' | Less than or equal to

## Logical Operators:

Operator | Description
-------- |  --------
'&&' | Logical and
'||' | Logical or
'!' | Logical not

## Bitwise Operators:

Operator | Description
-------- |  --------
'&' | AND
'|' | OR
'~' | NOT
'^' | XOR
'<<' | Zero fill left shift
'>>' | Signed right shift
'>>>' | Zero fill right shift

## Global Functions:

Function | Description
-------- |  --------
decodeURI() | Decodes a URI
decodeURIComponent() | Decodes a URI component
encodeURI() | Encodes a URI
encodeURIComponent() | Encodes a URI component
eval() | Evaluates a string and executes it as if it was script code
isFinite() | Determines whether a value is a finite number
isNaN() | Determines whether a value is an illegal number
Number() | Converts an object's value to a number
parseFloat() | Parses a string and returns a floating point number
parseInt() | Parses a string and returns an integer
String() | Converts an object's value to a string
typeof() | Returns the type of a variable

## Outputting Data:

Function | Description
-------- |  --------
alert() | Displays an alert box with a message and an OK button
confirm() | Displays a dialog box with a message and an OK and a Cancel button
console.log() | Writes an error message to the console
document.write() | Writes HTML expressions or JavaScript code to a document
prompt() | Displays a dialog box that prompts the visitor for input

## Loops:

Function | Description
-------- |  --------
for | Loops through a block of code a number of times
for/in | Loops through the properties of an object
for/of | Loops through the values of an iterable object
while | Loops through a block of code while a specified condition is true
do/while | Also loops through a block of code while a specified condition is true
break | Exits a loop
continue | Jumps out of a loop and starts at the top

## If/Else Statements:

Function | Description
-------- |  --------
if | Executes a block of code if a specified condition is true
else | Executes a block of code if a specified condition is false
else if | Executes a block of code if a specified condition is false
switch | Evaluates an expression, and executes the case that matches the expression

## String Methods:

Function | Description
-------- |  --------
charAt() | Returns the character at a specified index (position)
charCodeAt() | Returns the Unicode of the character at a specified index
concat() | Joins two or more strings, and returns a new joined strings
fromCharCode() | Converts Unicode values to characters
indexOf() | Returns the position of the first found occurrence of a specified value in a string
lastIndexOf() | Returns the position of the last found occurrence of a specified value in a string
match() | Searches a string for a match against a regular expression, and returns the matches
replace() | Searches a string for a specified value, or a regular expression, and returns a new string where the specified values are replaced
search() | Searches a string for a specified value, or regular expression, and returns the position of the match
slice() | Extracts a part of a string and returns a new string
split() | Splits a string into an array of substrings
substr() | Extracts the characters from a string, beginning at a specified start position, and through the specified number of character
substring() | Extracts the characters from a string, between two specified indices
toLowerCase() | Converts a string to lowercase letters
toUpperCase() | Converts a string to uppercase letters
valueOf() | Returns the primitive value of a string object

## Math Methods:

Function | Description
-------- |  --------
abs() | Returns the absolute value of a number
acos() | Returns the arccosine of a number
asin() | Returns the arcsine of a number
atan() | Returns the arctangent of a number
atan2() | Returns the arctangent of the quotient of its arguments
ceil() | Returns the smallest integer greater than or equal to a number
cos() | Returns the cosine of a number
exp() | Returns the value of Ex
floor() | Returns the largest integer less than or equal to a number
log() | Returns the natural logarithm (base E) of a number
max() | Returns the number with the highest value
min() | Returns the number with the lowest value
pow() | Returns the value of a number raised to a power
random() | Returns a random number between 0 and 1
round() | Rounds a number to the nearest integer
sin() | Returns the sine of a number
sqrt() | Returns the square root of a number
tan() | Returns the tangent of a number

## Math properties:

Property | Description
-------- |  --------
E | Returns Euler's number
LN2 | Returns the natural logarithm of 2
LN10 | Returns the natural logarithm of 10
LOG2E | Returns the base-2 logarithm of E
LOG10E | Returns the base-10 logarithm of E
PI | Returns PI
SQRT1_2 | Returns the square root of 1/2
SQRT2 | Returns the square root of 2

## Number properties:

Property | Description
-------- |  --------
MAX_VALUE | Returns the largest number possible in JavaScript
MIN_VALUE | Returns the smallest number possible in JavaScript
NaN | Represents "Not-a-Number" value
NEGATIVE_INFINITY | Represents negative infinity (returned on overflow)
POSITIVE_INFINITY | Represents infinity (returned on overflow)


