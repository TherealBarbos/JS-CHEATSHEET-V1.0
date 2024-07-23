# - JS-CHEATSHEET -

# Summary

- [JavaScript Introduction:](#javascript-introduction)
- [JavaScript Features:](#javascript-features)
- [JavaScript Advantages:](#javascript-advantages)
- [JavaScript Limitations:](#javascript-limitations)
- [JavaScript Syntax:](#javascript-syntax)
- [Including JavaScript in an HTML-Page:](#including-javascript-in-an-html-page)
- [Call an External JavaScript file:](#call-an-external-javascript-file)
- [Comments:](#comments)
- [Variables in JavaScript:](#variables-in-javascript)
- [Data Types](#data-types)
- [Objects:](#objects)
- [Array Methods:](#array-methods)
- [Basic Operators:](#basic-operators)
- [Comparison Operators:](#comparison-operators)
- [Logical Operators:](#logical-operators)
- [Bitwise Operators:](#bitwise-operators)
- [Global Functions:](#global-functions)
- [Outputting Data:](#outputting-data)
- [Loops:](#loops)
- [If/Else Statements:](#ifelse-statements)
- [String Methods:](#string-methods)
- [Math Methods:](#math-methods)
- [Math properties:](#math-properties)
- [Number properties:](#number-properties)
- [Number Methods:](#number-methods)
- [Set Data:](#set-data)
- [Set UTC Data:](#set-utc-data)
- [Get Data:](#get-data)
- [Get UTC Data:](#get-utc-data)
- [Regular Expressions:](#regular-expressions)
- [Regular Expression Modifiers:](#regular-expression-modifiers)
- [Regular Expression Patterns:](#regular-expression-patterns)
- [Regular Expression Quantifiers:](#regular-expression-quantifiers)
- [Error Handling:](#error-handling)
- [Mouse Events:](#mouse-events)
- [Keyboard Events:](#keyboard-events)
- [Frame Events:](#frame-events)
- [Form Events:](#form-events)
- [Drag Events:](#drag-events)
- [Clipboard Events:](#clipboard-events)
- [Media Events:](#media-events)
- [Form Validation:](#form-validation)
- [Web Storage:](#web-storage)
- [Web Workers:](#web-workers)
- [Web Sockets:](#web-sockets)


&uarr; [back to Top](#top)
## JavaScript Introduction:

JavaScript is a lightweight, interpreted programming language. It is designed for creating network-centric applications. It is complimentary to and integrated with Java. JavaScript is very easy to implement because it is integrated with HTML. It is open and cross-platform.

&uarr; [back to Top](#top)
## JavaScript Features:

1. **Interpreted Language:** JavaScript is an interpreted language, not compiled.
2. **Client-Side Language:** JavaScript is a client-side language. It runs on the client-side browser.
3. **Object-Based:** JavaScript is an object-based language.
4. **Lightweight:** JavaScript is lightweight.
5. **Versatile:** JavaScript is versatile.
6. **High Performance:** JavaScript is a high-performance language.
7. **Interpreted Language:** JavaScript is an interpreted language, not compiled.
8. **Client-Side Language:** JavaScript is a client-side language. It runs on the client-side browser.
9. **Object-Based:** JavaScript is an object-based language.
10. **Lightweight:** JavaScript is lightweight.
11. **Versatile:** JavaScript is versatile.
12. **High Performance:** JavaScript is a high-performance language.

&uarr; [back to Top](#top)
## JavaScript Advantages:

1. **Less Server Interaction:** You can validate user input before sending the page off to the server. This saves server traffic, which means less load on your server.
2. **Immediate Feedback to the Visitors:** They don't have to wait for a page reload to see if they have forgotten to enter something.
3. **Increased Interactivity:** You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.
4. **Richer Interfaces:** You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.
5. **Server Load:** You can reduce the server load by using JavaScript to validate form data before sending it to the server. This way, your server doesn't have to do as much work.

&uarr; [back to Top](#top)
## JavaScript Limitations:

1. **Client-Side Security:** You should be aware that JavaScript is executed on the client-side. So, it doesn't have the ability to interact with the database.
2. **Browser Support:** You have to write different code for different browsers. For example, Chrome, Firefox, and IE.
3. **No Multithreading or Multiprocessing:** JavaScript does not provide the facility for multithreading or multiprocessing.

&uarr; [back to Top](#top)
## JavaScript Syntax:

1. **Case Sensitivity:** JavaScript is case-sensitive.
2. **Semicolons:** JavaScript uses semicolons to separate statements.
3. **Whitespace:** JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.
4. **Comments:** JavaScript supports both single-line and multi-line comments.

&uarr; [back to Top](#top)
## JavaScript Variables:

1. **Variable:** A variable is a container for storing data values.
2. **Variable Naming:** A JavaScript identifier must start with a letter, underscore (_), or dollar sign ($). Subsequent characters can be letters, digits, underscores, or dollar signs.
3. **Variable Scope:** The scope of a variable is the region of your program in which it is defined. JavaScript variables have only two scopes: global and local.
4. **Variable Declaration:** You can declare a variable in JavaScript using the var keyword.
5. **Variable Initialization:** You can initialize a variable in JavaScript when you declare it.
6. **Variable Re-declaration:** You can re-declare a JavaScript variable without generating an error.
7. **Variable Hoisting:** JavaScript hoists variable declarations to the top of the current scope.



&uarr; [back to Top](#top)
## Including JavaScript in an HTML-Page:

```
<script type="text/javascript">
  // JS code gose here
</script>
```

&uarr; [back to Top](#top)
## Call an External JavaScript file:

```
<script src="myScript.js"></script>
```

&uarr; [back to Top](#top)
## Comments:

Single line comments : ``` // only single line comments ```

Multi-line comments : ``` /* comment here */ ```

&uarr; [back to Top](#top)
## Variables in JavaScript:

``` var : common variable, scoped to functions. ```

``` const : Immutable variable. ```

``` let : Mutable variable. ```

&uarr; [back to Top](#top)
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


&uarr; [back to Top](#top)
## Objects:

```
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
## Logical Operators:

Operator | Description
-------- |  --------
'&&' | Logical and
'||' | Logical or
'!' | Logical not

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
## Outputting Data:

Function | Description
-------- |  --------
alert() | Displays an alert box with a message and an OK button
confirm() | Displays a dialog box with a message and an OK and a Cancel button
console.log() | Writes an error message to the console
document.write() | Writes HTML expressions or JavaScript code to a document
prompt() | Displays a dialog box that prompts the visitor for input

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
## If/Else Statements:

Function | Description
-------- |  --------
if | Executes a block of code if a specified condition is true
else | Executes a block of code if a specified condition is false
else if | Executes a block of code if a specified condition is false
switch | Evaluates an expression, and executes the case that matches the expression

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
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

&uarr; [back to Top](#top)
## Number properties:

Property | Description
-------- |  --------
MAX_VALUE | Returns the largest number possible in JavaScript
MIN_VALUE | Returns the smallest number possible in JavaScript
NaN | Represents "Not-a-Number" value
NEGATIVE_INFINITY | Represents negative infinity (returned on overflow)
POSITIVE_INFINITY | Represents infinity (returned on overflow)

&uarr; [back to Top](#top)
## Number Methods:

Function | Description
-------- |  --------
toExponential() | Returns a string, with a number rounded and written using exponential notation
toFixed() | Returns a string, with a number written with a specified number of decimals
toPrecision() | Returns a string, with a number written with a specified length
toString() | Returns a number as a string
valueOf() | Returns a number as a number

&uarr; [back to Top](#top)
## Set Data:

Function | Description
-------- |  --------
setDate() | Sets the day of the month of a date object
setFullYear() | Sets the year of a date object
setMonth() | Sets the month of a date object
setHours() | Sets the hour of a date object
setMinutes() | Set the minutes of a date object
setSeconds() | Sets the seconds of a date object
setMilliseconds() | Sets the milliseconds of a date object
setTime() | Sets a date to a specified number of milliseconds after/before January 1, 1970

&uarr; [back to Top](#top)
## Set UTC Data:

Function | Description
-------- |  --------
setUTCDate() | Sets the day of the month of a date object, according to universal time
setUTCFullYear() | Sets the year of a date object, according to universal time
setUTCMonth() | Sets the month of a date object, according to universal time
setUTCHours() | Sets the hour of a date object, according to universal time
setUTCMinutes() | Sets the minutes of a date object, according to universal time
setUTCSeconds() | Sets the seconds of a date object, according to universal time
setUTCMilliseconds() | Sets the milliseconds of a date object, according to universal time

&uarr; [back to Top](#top)
## Get Data:

Function | Description
-------- |  --------
Date() | Returns the current date and time
Date ("YYYY-MM-DD") | Returns the date in the specified 
format
Date.now() | Returns the number of milliseconds since midnight Jan 1, 1970
getDate() | Returns the day of the month of a date object
getFullYear() | Returns the year of a date object
getMonth() | Returns the month of a date object
getDay() | Returns the day of the week of a date object
getHours() | Returns the hour of a date object
getMinutes() | Returns the minutes of a date object
getSeconds() | Returns the seconds of a date object
getMilliseconds() | Returns the milliseconds of a date object
getTime() | Returns the number of milliseconds since midnight Jan 1, 1970

&uarr; [back to Top](#top)
## Get UTC Data:

Function | Description
-------- |  --------
getUTCDate() | Returns the day of the month of a date object, according to universal time
getUTCFullYear() | Returns the year of a date object, according to universal time
getUTCMonth() | Returns the month of a date object, according to universal time
getUTCDay() | Returns the day of the week of a date object, according to universal time
getUTCHours() | Returns the hour of a date object, according to universal time
getUTCMinutes() | Returns the minutes of a date object, according to universal time
getUTCSeconds() | Returns the seconds of a date object, according to universal time
getUTCMilliseconds() | Returns the milliseconds of a date object, according to universal time

&uarr; [back to Top](#top)
## Regular Expressions:

Function | Description
-------- |  --------
exec() | Tests for a match in a string. Returns the first match
test() | Tests for a match in a string. Returns true or false
toString() | Returns the string value of the regular expression

&uarr; [back to Top](#top)
## Regular Expression Modifiers:

Modifier | Description
-------- |  --------
g | Perform a global match (find all matches rather than stopping after the first match)
i | Perform case-insensitive matching
m | Perform multiline matching

&uarr; [back to Top](#top)
## Regular Expression Patterns:

Pattern | Description
-------- |  --------
[abc] | Find any of the characters between the brackets
[^abc] | Find any character NOT between the brackets
[0-9] | Find any digit from 0 to 9
[A-Z] | Find any character from uppercase A to uppercase Z
[a-z] | Find any character from lowercase a to lowercase z
[A-z] | Find any character from uppercase A to lowercase z
[adgk] | Find any character in the given set
[^adgk] | Find any character NOT in the given set
(red|blue|green) | Find any of the alternatives specified

&uarr; [back to Top](#top)
## Regular Expression Quantifiers:

Quantifier | Description
-------- |  --------
n+ | Matches any string that contains at least one n
n* | Matches any string that contains zero or more occurrences of n
n? | Matches any string that contains zero or one occurrences of n
n{X} | Matches any string that contains a sequence of X n's
n{X,Y} | Matches any string that contains a sequence of X to Y n's
n{X,} | Matches any string that contains a sequence of at least X n's
n$ | Matches any string with n at the end of it
^n | Matches any string with n at the beginning of it
?=n | Matches any string that is followed by a specific string n
?!n | Matches any string that is not followed by a specific string n

&uarr; [back to Top](#top)
## Error Handling:

Function | Description
-------- |  --------
try | Implements error handling to a block of code
catch | Implements error handling to a block of code
throw | Creates custom errors
finally | Executes code, after try and catch, regardless of the result
Error | Creates an error object
Error object | Contains error name and error message

&uarr; [back to Top](#top)
### try

The try statement allows you to define a block of code to be tested for errors while it is being executed.

```
try {
  Block of code to try
}
catch(err) {
  Block of code to handle errors
}
```
```
try{
// Code taht may throw an error

let result = 10 / 0; // This will cause an error
console.log(result); // This will not be executed

} catch (error)  {
  // Catch and handle the error

  console.log("an error occured");

} finally {

  // This will always be executed
  // optional cleans up code

  
  console.log("This will always be executed");

};
```

&uarr; [back to Top](#top)
## Mouse Events:

Event |Description
-------- |--------
click | Occurs when the user clicks on an element
dbclick | Occurs when the user double-clicks on an element
mousedown | Occurs when the user presses a mouse button over an element
mouseup | Occurs when a user releases a mouse button over an element
mouseenter | Occurs when the pointer is moved onto an element
mouseover | Occurs when the pointer is moved onto an element, or onto one of its children
mouseout | Occurs when the pointer is moved out of an element, or out of one of its children
mouseleave | Occurs when the pointer is moved out of an element
mousemove | Occurs when the pointer is moving while it is over an element

&uarr; [back to Top](#top)
## Keyboard Events:

Event |Description
-------- |--------
keydown | Occurs when a keyboard key is pressed down
keyup | keyup | Occurs when a keyboard key is released
keypress* | Occurs when a keyboard key is pressed

*The 'keypress' event is deprecated and should not be used.

Deprecated: This feature is no longer recommended. Though some browsers might still support it, it may have already been removed from the relevant web standards, may be in the process of being dropped, or may only be kept for compatibility purposes. Avoid using it, and update existing code if possible; see the compatibility table at the bottom of this page to guide your decision. Be aware that this feature may cease to work at any time.

&uarr; [back to Top](#top)
## Frame Events:

Event | Description
-------- |  --------
abort | Occurs when the loading of an audio/video is aborted
beforeunload | Occurs before the document is about to be unloaded
error | Occurs when an error occurs while loading an audio/video
hashchange | Occurs when there has been changes to the anchor part of a URL
load | Occurs when an object has loaded
pageshow | Occurs when the browser starts to load the window
pagehide | Occurs when the browser starts to unload the window
resize | Occurs when the document view is resized
scroll | Occurs when the document view is scrolled
unload | Occurs once a page has unloaded (or the browser window has been closed)

&uarr; [back to Top](#top)
## Form Events:

Event | Description
-------- |  --------
blur | Occurs when an element loses focus
change | Occurs when the content of a form element, the selection, or the checked state have changed (for <input>, <select>, and <textarea>)
focus | Occurs when an element gets focus
focusin | Occurs when an element is about to get focus
focusout | Occurs when an element is about to lose focus
input | Occurs when an element gets user input
invalid | Occurs when an element is invalid
reset | Occurs when a form is reset
submit | Occurs when a form is submitted

&uarr; [back to Top](#top)
## Drag Events:

Event | Description
-------- |  --------
drag | Occurs when an element is being dragged
dragend | Occurs when the dragging of an element is finished
dragenter | Occurs when an element is being dragged over
dragleave | Occurs when an element leaves a drop target
dragover | Occurs when an element is being dragged over a drop target
dragstart | Occurs when the dragging of an element is about to start
drop | Occurs when an element is dropped

&uarr; [back to Top](#top)
## Clipboard Events:

Event | Description
-------- |  --------
copy | Occurs when the user copies the content of an element
cut | Occurs when the user cuts the content of an element
paste | Occurs when the user pastes some content in an element

&uarr; [back to Top](#top)
## Media Events:

Event | Description
-------- |  --------
abort | Occurs when the loading of an audio/video is aborted
canplay | Occurs when the browser can start playing the audio/video
canplaythrough | Occurs when the browser can play through the audio/video without stopping for buffering
durationchange | Occurs when the duration of the audio/video is changed
emptied | Occurs when the current playlist is empty
ended | Occurs when the current playlist is ended
error | Occurs when an error occurs when loading an audio/video
loadeddata | Occurs when the browser has loaded the current frame of the audio/video
loadedmetadata | Occurs when the browser has loaded meta data for the audio/video
loadstart | Occurs when the browser starts looking for the audio/video
pause | Occurs when the audio/video is paused
play | Occurs when the audio/video is playing after having been paused or stopped
playing | Occurs when the audio/video is playing without any pauses or stops
progress | Occurs when the browser is in the process of getting the media data
ratechange | Occurs when the playing speed of the audio/video is changed
seeked | Occurs when the user is finished moving/skipping to a new position in the audio/video
seeking | Occurs when the user starts moving/skipping to a new position in the audio/video
stalled | Occurs when the browser is trying to get media data, but data is not available
suspend | Occurs when the browser is intentionally not getting media data
timeupdate | Occurs when the current playback position has changed
volumechange | Occurs when the volume of the audio/video is changed
waiting | Occurs when the video stops because it needs to buffer the next frame


&uarr; [back to Top](#top)
## Form Validation:

Function | Description
-------- |  --------
checkValidity() | Returns false if an input element contains invalid data
setCustomValidity() | Sets the validationMessage property of an input element

&uarr; [back to Top](#top)
## Web Storage:

Function | Description
-------- |  --------
localStorage | Stores data with no expiration date
sessionStorage | Stores data for one session (data is lost when the browser tab is closed)

&uarr; [back to Top](#top)
## Web Workers:

Function | Description
-------- |  --------
Worker() | Creates a new worker
terminate() | Terminates a worker
onmessage | Defines an event listener for worker
postMessage() | Sends a message to a worker

&uarr; [back to Top](#top)
## Web Sockets:

Function | Description
-------- |  --------
WebSocket() | Creates a new WebSocket
send() | Sends a message to the server
onopen | Defines an event listener for connection
onmessage | Defines an event listener for message
onerror | Defines an event listener for error
onclose | Defines an event listener for close

&uarr; [back to Top](#top)