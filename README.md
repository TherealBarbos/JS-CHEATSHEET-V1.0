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
  
  ```
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
  ```
  