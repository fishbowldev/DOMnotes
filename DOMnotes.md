# How to Run JavaScript
Simply embed JS in your HTML document head between script tags.
Otherwise use the src attricbute of the script tag to import javascript tag.

# Statements in JavaScript
The following three are all the same to JS:

```
first statement
second statement
```

```
first statement; second statement;
```

```
first statement;
second statement;
```

# Comments in JavaScript
Anything that follows double-forward slash is a single line comment.

```
// this is a comment
```

```
statement // comment
```

Single line comments can also follow <!- in JavaSript.

```
<!- This is a comment.
```

```
<!- This is also a comment.>
```

Multiline comments are encased within /* and */

```
/* comment line 1
   comment line 2
   comment line 3 */
```

A comment in HTML requires closing <!- with ->

```
<!- This is a comment in HTML (and in JS) ->
```

# Variables in JavaScript
Variables can be easily **assigned** in different types.

```
mood = "happy";     // string type variable
age = 27;           // number type variable 
```

Variables can be reassigned values **dynamically**.

```
age = 28;           // variable age is reassigned to 28
```

## The assignment operator

= is the assignment operator which has been assigning values (data objects) to the variables.

## Containment

One way to think of assigning values to variables is that variables **contain** the value. The **container** can hold a different value, and so the variables can be redefined dynamically.

Variables can also be **declared** before assignment.
The following two are equivalent in declaring variables mood and age.

```
var mood;
var age;
```

And to save some time, 

```
var mood, age;      // mood and age currenlty hold the undefined data type
```

Variables can be declared and assigned simultaneously, so something like the following is also possible.

```
var mood = "happy"; age = 33;
```

# Data Types in JavaScript
There are many data types in JS:
* number
* float or decimal
* string
* array
* object

# Operators in JavaScript
Operators are broadly classified based on:
* number of values it operates on
* type of operation (arithmatic, etc.)

## Unary, Binary, and Ternary Operators
Unary operators operate on a single object.

Unary operators operate on two objects.

Ternary operators operate on three objects.

