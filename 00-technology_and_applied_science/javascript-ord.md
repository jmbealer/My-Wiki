---
author: Justin Bealer
date_created: 2022-06-26, 05-56-07
date_modified: 2024-09-18, 05-56-37
reference: 
description: 
aliases: 
tags: 
---
# Javascript-ord

[jsDataTypes](id:f3061f7f-5181-4011-b516-3100217a9a59)
[jsFunction](id:bd8b25b9-7a35-4fe9-a0a9-854ff153e692)
[jsOperator](id:85bb4b3e-8a1a-4ef7-9482-b867f6309760)
[jsControlFlow](id:cf20a83e-974e-48fc-9b34-f4dbd92a2bcd)

[jsLexicalStructure](id:a535a967-64fb-45fc-9fc1-3e801e441945) types,
values, and variable expressions and operators statements objects arrays
functions classes modules

## Introduction to JavaScript

is case sensitive. uses camelCasing starts with a lowercase letter for
the first word but every word after the first word begins with a capital
letter. There are no spaces between words.

thisIsCamelCasing;

script.js: All your JavaScript code will be written here

JavaScript was written by Brendan Eich to enhance static web pages.
JavaScript was built specifically as a tool for the web rather than for
building software.

Node.js - Node Node, which was created by Ryan Dahl in 2009, allows you
to run JavaScript projects on your machine. It also allows you to
configure the project environment.

JavaScript often abbreviated JS

JavaScript is a high-level, often just-in-time compiled language that
conforms to the ECMAScript standard. It has dynamic typing,
prototype-based object-orientation, and first-class functions. It is
multi-paradigm, supporting event-driven, functional, and imperative
programming styles. It has application programming interfaces (APIs) for
working with text, dates, regular expressions, standard data structures,
and the Document Object Model (DOM).

The ECMAScript standard does not include any input/output (I/O), such as
networking, storage, or graphics facilities. In practice, the web
browser or other runtime system provides JavaScript APIs for I/O.

JavaScript engines were originally used only in web browsers, but are
now core components of some servers and a variety of applications. The
most popular runtime system for this usage is Node.js.

## JavaScript Statements

JavaScript Programs A computer program is a list of "instructions" to be
"executed" by a computer. In a programming language, these programming
instructions are called statements. A JavaScript program is a list of
programming statements. In HTML, JavaScript programs are executed by the
web browser.

JavaScript Statements JavaScript statements are composed of: Values,
Operators, Expressions, Keywords, and Comments.

Most JavaScript programs contain many JavaScript statements. The
statements are executed, one by one, in the same order as they are
written. JavaScript programs (and JavaScript statements) are often
called JavaScript code.

Semicolons ; Semicolons separate JavaScript statements. Ending
statements with semicolon is not required, but highly recommended.

JavaScript White Space JavaScript ignores multiple spaces. You can add
white space to your script to make it more readable.

JavaScript Line Length and Line Breaks For best readability, programmers
often like to avoid code lines longer than 80 characters. If a
JavaScript statement does not fit on one line, the best place to break
it is after an operator:

JavaScript Code Blocks JavaScript statements can be grouped together in
code blocks, inside curly brackets {…}. The purpose of code blocks is to
define statements to be executed together.

### JavaScript Keywords

JavaScript statements often start with a keyword to identify the
JavaScript action to be performed.

Our Reserved Words Reference lists all JavaScript keywords.

Here is a list of some of the keywords you will learn about in this
tutorial:

JavaScript keywords are reserved words. Reserved words cannot be used as
names for variables.

JavaScript Statement Identifiers

JavaScript statements often start with a statement identifier to
identify the JavaScript action to be performed.

Statement identifiers are reserved words and cannot be used as variable
names (or any other things).

The following table lists all JavaScript statement identifiers:

Statement Description

break; - Exits a switch or a loop break labelname; - optional label
reference a class is type object template class className { // Declares
a class // class body } const varName = val; - Declares a block readonly
variable continue; - Breaks one iteration (in the loop) if a specified
condition occurs, and continues with the next iteration in the loop
continue labelname; - optional label reference debugger; - Stops the
execution of JavaScript, and calls (if available) the debugging function
The do…while statements combo defines a code block to be executed once,
and repeated as long as a condition is true. The do…while is used when
you want to run a code block at least one time. do { // Executes a block
of statements and repeats the block while a condition is true code block
to be executed } while (condition); for - defines a code block that is
executed as long as a condition is true. for (let i = 0; arr.length \<
i; i++){} for…in - iterates (loops) over the properties of an object.
for (i in object){} for…of - iterates (loops) over the values of any
iterable. for (i of array){}

function - Declares a function function funcName(parameters) {}

if - a block of code to be executed if a condition is true: if
(condition) { // block of code to be executed if the condition is true }

else - a block of code to be executed if the condition is false: if
(condition) { // block of code to be executed if the condition is true }
else { // block of code to be executed if the condition is false }

else if - a new condition if the first condition is false: if
(condition1) { // block of code to be executed if condition1 is true }
else if (condition2) { // block of code to be executed if the condition1
is false and condition2 is true } else { // block of code to be executed
if the condition1 is false and condition2 is false }

let name = value; - Declares a block variable return value; - stops the
execution of a function and returns a value.

switch - executes a block of code depending on different cases.
switch(expression){ case n: code block break; case n: code block break;
default: code block } throw expression; - statement defines a custom
error. throw Throws (generates) an error

try…catch…finally - handles errors without stopping JavaScript. try {
tryCode - Code block to run } catch(err) { catchCode - Code block to
handle errors } finally { finallyCode - Code block to be executed
regardless of the try result }

try - defines the code block to run (to try). catch - defines a code
block to handle any error. finally - defines a code block to run
regardless of the result.

var name = value; - Declares a variable while - creates a loop (araund a
code block) that is executed while a condition is true. while
(condition) { code block to be executed }

### Js Statements Example

Example let x, y, z; // Statement 1 x = 5; // Statement 2 y = 6; //
Statement 3 z = x + y; // Statement 4

This statement tells the browser to write "Hello Dolly." inside an HTML
element with id="demo": Example
document.getElementById("demo").innerHTML = "Hello Dolly.";

Add a semicolon at the end of each executable statement: Examples let a,
b, c; // Declare 3 variables a = 5; // Assign the value 5 to a b = 6; //
Assign the value 6 to b c = a + b; // Assign the sum of a and b to c

When separated by semicolons, multiple statements on one line are
allowed: a = 5; b = 6; c = a + b;

The following lines are equivalent: let person = "Hege"; let
person="Hege";

A good practice is to put spaces around operators ( = + - \* / ): let x
= y + z;

If a JavaScript statement does not fit on one line, the best place to
break it is after an operator:

Example document.getElementById("demo").innerHTML = "Hello Dolly!";
JavaScript Code Blocks

Example document.getElementById("demo").innerHTML = "Hello Dolly!";

One place you will find statements grouped together in blocks, is in
JavaScript functions: Example function myFunction() {
document.getElementById("demo1").innerHTML = "Hello Dolly!";
document.getElementById("demo2").innerHTML = "How are you?"; }

## JavaScript Syntax

JavaScript syntax is the set of rules, how JavaScript programs are
constructed:

JavaScript Values The JavaScript syntax defines two types of values:
Fixed values Variable values

Fixed values are called Literals. Variable values are called Variables.

JavaScript Literals The two most important syntax rules for fixed values
are:

1. Numbers are written with or without decimals:

10.50 1001

1. Strings are text, written within double or single quotes:

"John Doe" 'John Doe'

JavaScript Expressions An expression is a combination of values,
variables, and operators, which computes to a value. The computation is
called an evaluation. For example, 5 \* 10 evaluates to 50: 5 \* 10
Expressions can also contain variable values: x \* 10 The values can be
of various types, such as numbers and strings. For example, "John" + "
" + "Doe", evaluates to "John Doe": "John" + " " + "Doe"

JavaScript Keywords JavaScript keywords are used to identify actions to
be performed. The let keyword tells the browser to create variables: let
x, y; x = 5 + 6; y = x \* 10; The var keyword also tells the browser to
create variables: var x, y; x = 5 + 6; y = x \* 10;

In these examples, using var or let will produce the same result. You
will learn more about var and let later in this tutorial.

JavaScript Identifiers / Names Identifiers are JavaScript names.
Identifiers are used to name variables and keywords, and functions. The
rules for legal names are the same in most programming languages. A
JavaScript name must begin with: A letter (A-Z or a-z) A dollar sign
(\$) Or an underscore (\_) Subsequent characters may be letters, digits,
underscores, or dollar signs. Note Numbers are not allowed as the first
character in names. This way JavaScript can easily distinguish
identifiers from numbers.

JavaScript is Case Sensitive All JavaScript identifiers are case
sensitive. The variables lastName and lastname, are two different
variables: let lastname, lastName; lastName = "Doe"; lastname =
"Peterson";

JavaScript and Camel Case Historically, programmers have used different
ways of joining multiple words into one variable name: Hyphens:
first-name, last-name, master-card, inter-city. Hyphens are not allowed
in JavaScript. They are reserved for subtractions. Underscore:
first<sub>name</sub>, last<sub>name</sub>, master<sub>card</sub>,
inter<sub>city</sub>. Upper Camel Case (Pascal Case): FirstName,
LastName, MasterCard, InterCity. Lower Camel Case: JavaScript
programmers tend to use camel case that starts with a lowercase letter:
firstName, lastName, masterCard, interCity.

JavaScript Character Set JavaScript uses the Unicode character set.
Unicode covers (almost) all the characters, punctuations, and symbols in
the world.

JavaScript Identifiers All JavaScript variables must be identified with
unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names
(age, sum, totalVolume).

The general rules for constructing names for variables (unique
identifiers) are:

Names can contain letters, digits, underscores, and dollar signs. Names
must begin with a letter Names can also begin with \$ and \_ (but we
will not use it in this tutorial) Names are case sensitive (y and Y are
different variables) Reserved words (like JavaScript keywords) cannot be
used as names

Note JavaScript identifiers are case-sensitive.

## What Are Js Variables? Wip

Variables are containers for storing data (storing data values).

A variable behaves as if it was the value that it contains.

Variables hold reusable data in a program and associate it with a name.

Variables are stored in memory.

Variables allow computers to store and manipulate data in a dynamic
fashion. They do this by using a "label" to point to the data rather
than using the data itself.

In computer science, data is anything that is meaningful to the
computer.

Two steps: Declaration (var, let, const) Assignment (= assignment
operator)

An equal sign is used to assign values to variables.

Declare JavaScript Variables Declaring a JavaScript Variable

Creating a variable in JavaScript is called "declaring" a variable.

JavaScript uses the keywords var, let and const to declare variables.

After the declaration, the variable has no value (technically it is
undefined). A variable declared without a value will have the value
undefined.

It's a good programming practice to declare all variables at the
beginning of a script.

In computer programs, variables are often declared without a value. The
value can be something that has to be calculated, or something that will
be provided later, like user input.

JavaScript Dollar Sign \$ Since JavaScript treats a dollar sign as a
letter, identifiers containing \$ are valid variable names: Example let
\$ = "Hello World"; let \$\$\$ = 2; let \$myMoney = 5; Using the dollar
sign is not very common in JavaScript, but professional programmers
often use it as an alias for the main function in a JavaScript library.
In the JavaScript library jQuery, for instance, the main function \$ is
used to select HTML elements. In jQuery \$("p"); means "select all p
elements".

JavaScript Underscore (\_) Since JavaScript treats underscore as a
letter, identifiers containing \_ are valid variable names: Example let
<sub>lastName</sub> = "Johnson"; let <sub>x</sub> = 2; let
<sub>100</sub> = 5; Using the underscore is not very common in
JavaScript, but a convention among professional programmers is to use it
as an alias for "private (hidden)" variables.

That's where const and let can help. They prevent developers from making
unintended mistakes when declaring their variables.

What method should you use?

At this point, you might be wondering which method of declaring
variables you should use. Here's the process that you should follow when
determining whether to use let, const, or var:

Use const primarily; this will be your go-to. Moving forward, you'll
want to declare most of your variables using const. Use let if you need
to reassign a value. This is a common requirement during for loops and
sometimes with if statements. Don't use var unless necessary, like when
working in a codebase that uses it. However, that will likely only
happen in the distant future. As mentioned above, there are other
reasons to use (and to not use) var, but those will be covered in a
different lesson. For now, just avoid it.

var makes variable global even in functions

Initializing Variables with the Assignment Operator It is common to
initialize a variable to an initial value in the same line as it is
declared. var myVar = 0; Creates a new variable called myVar and assigns
it an initial value of 0. Define a variable a with var and initialize it
to a value of 9.

Understanding Uninitialized Variables When JavaScript variables are
declared, they have an initial value of undefined. If you do a
mathematical operation on an undefined variable your result will be NaN
which means "Not a Number". If you concatenate a string with an
undefined variable, you will get a string of undefined.

Compare Scopes of the var and let Keywords If you are unfamiliar with
let, check out this challenge about the difference bewteen let and var.
When you declare a variable with the var keyword, it is declared
globally, or locally if declared inside a function. The let keyword
behaves similarly, but with some extra features. When you declare a
variable with the let keyword inside a block, statement, or expression,
its scope is limited to that block, statement, or expression. For
example: var numArray = \[\]; for (var i = 0; i \< 3; i++) {
numArray.push(i); } console.log(numArray); console.log(i); Here the
console will display the values \[0, 1, 2\] and 3. With the var keyword,
i is declared globally. So when i++ is executed, it updates the global
variable. This code is similar to the following: var numArray = \[\];
var i; for (i = 0; i \< 3; i++) { numArray.push(i); }
console.log(numArray); console.log(i); Here the console will display the
values \[0, 1, 2\] and 3. This behavior will cause problems if you were
to create a function and store it for later use inside a for loop that
uses the i variable. This is because the stored function will always
refer to the value of the updated global i variable. var printNumTwo;
for (var i = 0; i \< 3; i++) { if (i `=` 2) { printNumTwo = function() {
return i; }; } } console.log(printNumTwo()); Here the console will
display the value 3. As you can see, printNumTwo() prints 3 and not 2.
This is because the value assigned to i was updated and the
printNumTwo() returns the global i and not the value i had when the
function was created in the for loop. The let keyword does not follow
this behavior: let printNumTwo; for (let i = 0; i \< 3; i++) { if (i `=`
2) { printNumTwo = function() { return i; }; } }
console.log(printNumTwo()); console.log(i); Here the console will
display the value 2, and an error that i is not defined. i is not
defined because it was not declared in the global scope. It is only
declared within the for loop statement. printNumTwo() returned the
correct value because three different i variables with unique values (0,
1, and 2) were created by the let keyword within the loop statement.

### Var Keyword

var keyword isnt used anymore, and you should avoid using them. var
variables can be re-declared and updated. The var keyword is used in
pre-ES6 versions of JS. Explore Differences Between the var and let
Keywords One of the biggest problems with declaring variables with the
var keyword is that you can easily overwrite variable declarations: var
camper = "James"; var camper = "David"; console.log(camper); In the code
above, the camper variable is originally declared as James, and is then
overridden to be David. The console then displays the string David. In a
small application, you might not run into this type of problem. But as
your codebase becomes larger, you might accidentally overwrite a
variable that you did not intend to. Because this behavior does not
throw an error, searching for and fixing bugs becomes more difficult.

The var keyword In the past, variables were declared with the keyword
var. Here is what var looks like in action: var productName = "Jogger
Sweatpants"; Just like with let, variables created with the var keyword
can be reassigned. However, var doesn't have the same restrictions as
let when it comes to declaring variables with the same name. See the
example below: var productName = "Jogger Sweatpants"; productName =
"Men's Jogger Sweatpants"; var productName = "Woman's Jogger
Sweatpants"; Because var is an older method of declaring variables, you
will often see var referenced in older code. However, you shouldn't use
var in your code unless you have a very specific reason to do so.

### Let Keyword

let variables, however, can be updated. let is the preferred way to
declare a variable when it can be reassigned A keyword called let was
introduced in ES6, a major update to JavaScript, to solve this potential
issue with the var keyword. If you replace var with let in the code
above, it results in an error: let camper = "James"; let camper =
"David"; The error can be seen in your browser console. So unlike var,
when you use let, a variable with the same name can only be declared
once.

JavaScript Let

The let keyword was introduced in ES6 (2015).

Variables defined with let cannot be Redeclared.

Variables defined with let must be Declared before use.

Variables defined with let have Block Scope. Cannot be Redeclared

Variables defined with let cannot be redeclared.

You cannot accidentally redeclare a variable.

With let you can not do this: Example let x = "John Doe";

let x = 0;

// SyntaxError: 'x' has already been declared

With var you can: Example var x = "John Doe";

var x = 0; Block Scope

Before ES6 (2015), JavaScript had only Global Scope and Function Scope.

ES6 introduced two important new JavaScript keywords: let and const.

These two keywords provide Block Scope in JavaScript.

Variables declared inside a { } block cannot be accessed from outside
the block: Example { let x = 2; } // x can NOT be used here

Variables declared with the var keyword can NOT have block scope.

Variables declared inside a { } block can be accessed from outside the
block. Example { var x = 2; } // x CAN be used here Redeclaring
Variables

Redeclaring a variable using the var keyword can impose problems.

Redeclaring a variable inside a block will also redeclare the variable
outside the block: Example var x = 10; // Here x is 10

{ var x = 2; // Here x is 2 }

// Here x is 2

Redeclaring a variable using the let keyword can solve this problem.

Redeclaring a variable inside a block will not redeclare the variable
outside the block: Example let x = 10; // Here x is 10

{ let x = 2; // Here x is 2 }

// Here x is 10 Browser Support

The let keyword is not fully supported in Internet Explorer 11 or
earlier.

The following table defines the first browser versions with full support
for the let keyword:

Chrome 49 Edge 12 Firefox 44 Safari 11 Opera 36 Mar, 2016 Jul, 2015 Jan,
2015 Sep, 2017 Mar, 2016 Redeclaring

Redeclaring a JavaScript variable with var is allowed anywhere in a
program: Example var x = 2; // Now x is 2

var x = 3; // Now x is 3

With let, redeclaring a variable in the same block is NOT allowed:
Example var x = 2; // Allowed let x = 3; // Not allowed

{ let x = 2; // Allowed let x = 3 // Not allowed }

{ let x = 2; // Allowed var x = 3 // Not allowed }

Redeclaring a variable with let, in another block, IS allowed: Example
let x = 2; // Allowed

{ let x = 3; // Allowed }

{ let x = 4; // Allowed } Let Hoisting

Variables defined with var are hoisted to the top and can be initialized
at any time.

Meaning: You can use the variable before it is declared: Example

This is OK: carName = "Volvo"; var carName;

If you want to learn more about hoisting, study the chapter JavaScript
Hoisting.

Variables defined with let are also hoisted to the top of the block, but
not initialized.

Meaning: Using a let variable before it is declared will result in a
ReferenceError: Example carName = "Saab"; let carName = "Volvo";

The variable total is declared with the let keyword.

This is a value that can be changed. Just Like Algebra

Just like in algebra, variables hold values: let x = 5; let y = 6;

Just like in algebra, variables are used in expressions: let z = x + y;

From the example above, you can guess that the total is calculated to be
11.

The let keyword As you've learned, the let keyword is used to declare
variables in JavaScript. Here's some refresher code for your review: let
price = 9.99; You can also reassign variables that have already been
created using let. Here's an example: let price = 9.99; price = 8.5;
However, if you declare a variable with let, you cannot use let to later
define that same variable. See the error below: let price = 9.99; let
price = 8.5; //\> Uncaught SyntaxError: Identifier 'price' has already
been declared This SyntaxError is pretty useful. It will stop you from
accidentally recreating the same variable later on in your program when
you don't intend to do so.

### Const Keyword

const keyword stand for constants const keyword used to declare
variables that can't be changed const pi = 3.14; pi = 3.1415; // This
will throw an error because const variables can't be updated const is
the preferred way to declare a variable with a constant value.

Declare a Read-Only Variable with the const Keyword const has all the
awesome features that let has, with the added bonus that variables
declared using const are read-only. They are a constant value, which
means that once a variable is assigned with const, it cannot be
reassigned: const FAV<sub>PET</sub> = "Cats"; FAV<sub>PET</sub> =
"Dogs"; The console will display an error due to reassigning the value
of FAV<sub>PET</sub>. You should always name variables you don't want to
reassign using the const keyword. This helps when you accidentally
attempt to reassign a variable that is meant to stay constant. Note: It
is common for developers to use uppercase variable identifiers for
immutable values and lowercase or camelCase for mutable values (objects
and arrays). You will learn more about objects, arrays, and immutable
and mutable values in later challenges. Also in later challenges, you
will see examples of uppercase, lowercase, or camelCase variable
identifiers.

JavaScript Const

The const keyword was introduced in ES6 (2015).

Variables defined with const cannot be Redeclared.

Variables defined with const cannot be Reassigned.

Variables defined with const have Block Scope. Cannot be Reassigned

A const variable cannot be reassigned: Example const PI =
3.141592653589793; PI = 3.14; // This will give an error PI = PI + 10;
// This will also give an error Must be Assigned

JavaScript const variables must be assigned a value when they are
declared: Correct const PI = 3.14159265359; Incorrect const PI; PI =
3.14159265359; When to use JavaScript const?

As a general rule, always declare a variable with const unless you know
that the value will change.

Use const when you declare:

A new Array A new Object A new Function A new RegExp

Constant Objects and Arrays

The keyword const is a little misleading.

It does not define a constant value. It defines a constant reference to
a value.

Because of this you can NOT:

Reassign a constant value Reassign a constant array Reassign a constant
object

But you CAN: Change the elements of constant array Change the properties
of constant object

Constant Arrays

You can change the elements of a constant array: Example // You can
create a constant array: const cars = \["Saab", "Volvo", "BMW"\];

// You can change an element: cars\[0\] = "Toyota";

// You can add an element: cars.push("Audi");

But you can NOT reassign the array: Example const cars = \["Saab",
"Volvo", "BMW"\];

cars = \["Toyota", "Volvo", "Audi"\]; // ERROR Constant Objects

You can change the properties of a constant object: Example // You can
create a const object: const car = {type:"Fiat", model:"500",
color:"white"};

// You can change a property: car.color = "red";

// You can add a property: car.owner = "Johnson";

But you can NOT reassign the object: Example const car = {type:"Fiat",
model:"500", color:"white"};

car = {type:"Volvo", model:"EX60", color:"red"}; // ERROR Browser
Support

The const keyword is not supported in Internet Explorer 10 or earlier.

The following table defines the first browser versions with full support
for the const keyword:

Chrome 49 IE 11 / Edge Firefox 36 Safari 10 Opera 36 Mar, 2016 Oct, 2013
Feb, 2015 Sep, 2016 Mar, 2016 Block Scope

Declaring a variable with const is similar to let when it comes to Block
Scope.

The x declared in the block, in this example, is not the same as the x
declared outside the block: Example const x = 10; // Here x is 10

{ const x = 2; // Here x is 2 }

// Here x is 10

You can learn more about block scope in the chapter JavaScript Scope.
Redeclaring

Redeclaring a JavaScript var variable is allowed anywhere in a program:
Example var x = 2; // Allowed var x = 3; // Allowed x = 4; // Allowed

Redeclaring an existing var or let variable to const, in the same scope,
is not allowed: Example var x = 2; // Allowed const x = 2; // Not
allowed

{ let x = 2; // Allowed const x = 2; // Not allowed }

{ const x = 2; // Allowed const x = 2; // Not allowed }

Reassigning an existing const variable, in the same scope, is not
allowed: Example const x = 2; // Allowed x = 2; // Not allowed var x =
2; // Not allowed let x = 2; // Not allowed const x = 2; // Not allowed

{ const x = 2; // Allowed x = 2; // Not allowed var x = 2; // Not
allowed let x = 2; // Not allowed const x = 2; // Not allowed }

Redeclaring a variable with const, in another scope, or in another
block, is allowed: Example const x = 2; // Allowed

{ const x = 3; // Allowed }

{ const x = 4; // Allowed } Const Hoisting

Variables defined with var are hoisted to the top and can be initialized
at any time.

Meaning: You can use the variable before it is declared: Example

This is OK: carName = "Volvo"; var carName;

If you want to learn more about hoisting, study the chapter JavaScript
Hoisting.

Variables defined with const are also hoisted to the top, but not
initialized.

Meaning: Using a const variable before it is declared will result in a
ReferenceError: Example alert (carName); const carName = "Volvo";

When to Use JavaScript const?

If you want a general rule: always declare variables with const.

If you think the value of the variable can change, use let.

In this example, price1, price2, and total, are variables: Example const
price1 = 5; const price2 = 6; let total = price1 + price2;

The two variables price1 and price2 are declared with the const keyword.

These are constant values and cannot be changed.

The const keyword const size = "M"; const size = "L"; //\> Uncaught
SyntaxError: Identifier 'size' has already been declared However, with
const, you also can't reassign the value. See below: const size = "M";
size = "S"; //\> Uncaught TypeError: Assignment to constant variable.

Warning: Using const with arrays and objects But const also has some
other traits that are worth discussing. And when it comes to arrays and
objects, using const can be a bit tricky.

Take a look at the following code. It works as you may expect: const
product = { priceInCents: 2100, name: "Yellow Beanie", size: "M" };
product = { priceInCents: 2100, name: "Red Beanie", size: "L" }; //\>
Uncaught TypeError: Assignment to constant variable. In the above case,
you aren't able to reassign the value of const, as intended. The
following code, on the other hand, does run.

const product = { priceInCents: 2100, name: "Yellow Beanie", size: "M"
}; product.name = "Red Beanie"; product.size = "L"; Although you can't
reassign the variable completely with const, you can change the values
inside of the object. The same goes for arrays. Take a look:

const sizes = \[8, 10, 12, 14\];

sizes\[4\] = 16;

Mutate an Array Declared with const

If you are unfamiliar with const, check out this challenge about the
const keyword.

The const declaration has many use cases in modern JavaScript.

Some developers prefer to assign all their variables using const by
default, unless they know they will need to reassign the value. Only in
that case, they use let.

However, it is important to understand that objects (including arrays
and functions) assigned to a variable using const are still mutable.
Using the const declaration only prevents reassignment of the variable
identifier.

const s = \[5, 6, 7\]; s = \[1, 2, 3\]; s\[2\] = 45; console.log(s);

s = \[1, 2, 3\] will result in an error. The console.log will display
the value \[5, 6, 45\].

As you can see, you can mutate the object \[5, 6, 7\] itself and the
variable s will still point to the altered array \[5, 6, 45\]. Like all
arrays, the array elements in s are mutable, but because const was used,
you cannot use the variable identifier s to point to a different array
using the assignment operator.

An array is declared as const s = \[5, 7, 2\]. Change the array to \[2,
5, 7\] using various element assignments.

### Js Variables Examples

``` javascript
// declare a variable myVar without initial value:
let myVar; // returns undefined
// assign myVar with value 11:
myVar = 11; // returns 11

// declaring and initializing a variable myVar with string foo
let myVar = "foo"; // returns foo

// declare a constants variables named PI with value 3.14
const PI = 3.14; // returns 3.14; readonly
// updating constant variable
PI = 11 // returns a error

// var keyword is bad practice
// declare a variable named myVar without initial value:
var myVar; // returns undefined
// assign myVar with value 33:
myVar = 33; // returns 33
// declaring and initializing a variable myVar with string foo
var myVar = "foo"; // returns foo

// Assigning the Value of One Variable to Another
// declare variable named myStr
let myStr; // returns undefined
// assign myVar to myStr:
myStr = myVar; // returns foo

```

In this example, x is defined as a variable. Then, x is assigned (given)
the value 6: let x; x = 6;

In this example, x, y, and z, are variables, declared with the var
keyword: Example var x = 5; var y = 6; var z = x + y;

In this example, x, y, and z, are variables, declared with the let
keyword: Example let x = 5; let y = 6; let z = x + y;

In this example, x, y, and z, are undeclared variables: Example x = 5; y
= 6; z = x + y;

From all the examples above, you can guess:

x stores the value 5 y stores the value 6 z stores the value 11

You declare a JavaScript variable with the var or the let keyword: var
carName; or: let carName;

To assign a value to the variable, use the equal sign: carName =
"Volvo";

You can also assign a value to the variable when you declare it: let
carName = "Volvo";

One Statement, Many Variables You can declare many variables in one
statement.

Start the statement with let and separate the variables by comma:
Example let person = "John Doe", carName = "Volvo", price = 200;

A declaration can span multiple lines: Example let person = "John Doe",
carName = "Volvo", price = 200; Value = undefined

Re-Declaring JavaScript Variables If you re-declare a JavaScript
variable declared with var, it will not lose its value. The variable
carName will still have the value "Volvo" after the execution of these
statements: Example var carName = "Volvo"; var carName; Note You cannot
re-declare a variable declared with let or const.

This will not work: let carName = "Volvo"; let carName;

## Js Modules Wip

Modules JavaScript modules allow you to break up your code into separate
files.

This makes it easier to maintain the code-base.

JavaScript modules rely on the import and export statements.

Export You can export a function or variable from any file.

Let us create a file named person.js, and fill it with the things we
want to export.

There are two types of exports: Named and Default.

Named Exports You can create named exports two ways. In-line
individually, or all at once at the bottom.

In-line individually: person.js

export const name = "Jesse"; export const age = 40; All at once at the
bottom: person.js

const name = "Jesse"; const age = 40;

export {name, age}; Default Exports Let us create another file, named
message.js, and use it for demonstrating default export.

You can only have one default export in a file.

Example message.js

const message = () =\> { const name = "Jesse"; const age = 40; return
name + ' is ' + age + 'years old.'; };

export default message; Import You can import modules into a file in two
ways, based on if they are named exports or default exports.

Named exports are constructed using curly braces. Default exports are
not.

Import from named exports Import named exports from the file person.js:

import { name, age } from "./person.js";

Import from default exports Import a default export from the file
message.js:

import message from "./message.js";

Note Modules only work with the HTTP(s) protocol.

A web-page opened via the <file://> protocol cannot use import / export.

## Scope

Global Scope and Functions In JavaScript, scope refers to the visibility
of variables. Variables which are defined outside of a function block
have Global scope. This means, they can be seen everywhere in your
JavaScript code. Variables which are declared without the let or const
keywords are automatically created in the global scope. This can create
unintended consequences elsewhere in your code or when running a
function again. You should always declare your variables with let or
const. Using let or const, declare a global variable named myGlobal
outside of any function. Initialize it with a value of 10. Inside
function fun1, assign 5 to oopsGlobal without using the let or const
keywords.

Local Scope and Functions Variables which are declared within a
function, as well as the function parameters, have local scope. That
means they are only visible within that function. Here is a function
myTest with a local variable called loc. function myTest() { const loc =
"foo"; console.log(loc); } myTest(); console.log(loc); The myTest()
function call will display the string foo in the console. The
console.log(loc) line (outside of the myTest function) will throw an
error, as loc is not defined outside of the function. The editor has two
console.logs to help you see what is happening. Check the console as you
code to see how it changes. Declare a local variable myVar inside
myLocalScope and run the tests. Note: The console will still display
ReferenceError: myVar is not defined, but this will not cause the tests
to fail.

Global vs. Local Scope in Functions It is possible to have both local
and global variables with the same name. When you do this, the local
variable takes precedence over the global variable. In this example:
const someVar = "Hat"; function myFun() { const someVar = "Head"; return
someVar; } The function myFun will return the string Head because the
local version of the variable is present. Add a local variable to
myOutfit function to override the value of outerWear with the string
sweater.

Global scope The scope that contains all other scopes

variables created outside of functions are global variables created
inside of functions are local Function parameters act like variables
created inside a function each time call function it creates a new
scope.

shadowing javascript looks for a scope inside function then outside
inside beat outside

Summary: Scope rules Here's a summary of the scope rules that you've
learned so far: Every variable is part of a scope. If the variable is
created outside of any function, it's stored in the global scope.
Variables in the global scope are visible everywhere. Each time that a
function is called, it creates a new scope. If the variable is created
inside a function, it gets stored inside the function's scope. Variables
in a function scope are only visible inside the function. The function
scope disappears when the function ends. Parameters get assigned
function scope, as if they were variables created inside the function.
Parameters get assigned the values from the arguments when the function
is called. Scope is pretty complicated. In this lesson, you learned some
essential scope rules. But there are still more scope rules, and you'll
learn those later.

JavaScript Scope

Scope determines the accessibility (visibility) of variables.

JavaScript has 3 types of scope:

Block scope Function scope Global scope

Block Scope

Before ES6 (2015), JavaScript had only Global Scope and Function Scope.

ES6 introduced two important new JavaScript keywords: let and const.

These two keywords provide Block Scope in JavaScript.

Variables declared inside a { } block cannot be accessed from outside
the block: Example { let x = 2; } // x can NOT be used here

Variables declared with the var keyword can NOT have block scope.

Variables declared inside a { } block can be accessed from outside the
block. Example { var x = 2; } // x CAN be used here Local Scope

Variables declared within a JavaScript function, become LOCAL to the
function. Example // code here can NOT use carName

function myFunction() { let carName = "Volvo"; // code here CAN use
carName }

// code here can NOT use carName

Local variables have Function Scope:

They can only be accessed from within the function.

Since local variables are only recognized inside their functions,
variables with the same name can be used in different functions.

Local variables are created when a function starts, and deleted when the
function is completed. Function Scope

JavaScript has function scope: Each function creates a new scope.

Variables defined inside a function are not accessible (visible) from
outside the function.

Variables declared with var, let and const are quite similar when
declared inside a function.

They all have Function Scope: function myFunction() { var carName =
"Volvo"; // Function Scope } function myFunction() { let carName =
"Volvo"; // Function Scope } function myFunction() { const carName =
"Volvo"; // Function Scope } Global JavaScript Variables

A variable declared outside a function, becomes GLOBAL. Example let
carName = "Volvo"; // code here can use carName

function myFunction() { // code here can also use carName }

A global variable has Global Scope:

All scripts and functions on a web page can access it. Global Scope

Variables declared Globally (outside any function) have Global Scope.

Global variables can be accessed from anywhere in a JavaScript program.

Variables declared with var, let and const are quite similar when
declared outside a block.

They all have Global Scope: var x = 2; // Global scope let x = 2; //
Global scope const x = 2; // Global scope JavaScript Variables

In JavaScript, objects and functions are also variables.

Scope determines the accessibility of variables, objects, and functions
from different parts of the code. Automatically Global

If you assign a value to a variable that has not been declared, it will
automatically become a GLOBAL variable.

This code example will declare a global variable carName, even if the
value is assigned inside a function. Example myFunction();

// code here can use carName

function myFunction() { carName = "Volvo"; } Strict Mode

All modern browsers support running JavaScript in "Strict Mode".

You will learn more about how to use strict mode in a later chapter of
this tutorial.

In "Strict Mode", undeclared variables are not automatically global.
Global Variables in HTML

With JavaScript, the global scope is the JavaScript environment.

In HTML, the global scope is the window object.

Global variables defined with the var keyword belong to the window
object: Example var carName = "Volvo"; // code here can use
window.carName

Global variables defined with the let keyword do not belong to the
window object: Example let carName = "Volvo"; // code here can not use
window.carName Warning

Do NOT create global variables unless you intend to.

Your global variables (or functions) can overwrite window variables (or
functions). Any function, including the window object, can overwrite
your global variables and functions. The Lifetime of JavaScript
Variables

The lifetime of a JavaScript variable starts when it is declared.

Function (local) variables are deleted when the function is completed.

In a web browser, global variables are deleted when you close the
browser window (or tab). Function Arguments

Function arguments (parameters) work as local variables inside
functions.

### Scope Thinkful

Sibling scopes Two or more scopes that share a common parent scope

Complex scope The following video breaks down how to evaluate functions
with complicated scope and diagram the scope of programs. Start by
watching the video, and then read through the rest of the lesson and
complete the practice work required. This will give you a full
understanding of these concepts.

When you use let and const, you can easily separate scope by simply
looking for the curly brackets {}. Each pair of curly brackets gives you
a new level of scope.

Additionally, anything inside of a set of curly brackets can access
reference variables that are set outside of it. See if you can separate
the scopes in the code sample below:

const DISCOUNT<sub>PERCENTAGE</sub> = 0.15; function
discountPricesInCents(products) { const result = \[\];

for (let i = 0; i \< products.length; i++) { const product =
products\[i\]; let price = product.priceInCents; if
(DISCOUNT<sub>PERCENTAGE</sub> \> 0) { const multiplier = 1 -
DISCOUNT<sub>PERCENTAGE</sub>; price = product.priceInCents \*
multiplier; } result.push(price); }

return result; }

The above code relies on different rules for block scope and global
scope. Here are the details:

In the discountPricesInCents() function, you can access
DISCOUNT<sub>PERCENTAGE</sub> because it's part of the global scope.
Later on, if you were to call discountPricesInCents(), you would be
accessing it from the global scope. In the for loop statement, you're
able to access the products parameter because it is shared inside the
function scope. If you tried to log products outside of the function,
you would get an error. Inside of the for loop, you're able to access
products and DISCOUNT<sub>PERCENTAGE</sub> because they are both in
outer scopes. However, i, product, and price are accessible only within
the for loop. You can't access those variables outside of the curly
brackets. Finally, multiplier is accessible only inside of the if
statement. It can't be accessed outside of that statement.

Diagramming scope As you can see above, a complex scope can be hard to
understand. To gain some clarity, developers often find it useful to
diagram out the scope for a particular function or program. Here's one
way to diagram scope: Diagramming scope

The above diagram demonstrates the following: Each distinct background
color represents a level of scope. For example, the if statement scope
is enclosed inside of the for loop scope. At each arrow, a new scope is
introduced. For example, inside of the function scope is a for loop
scope. Each scope has access to the variables of its containers. For
example, the function scope has access to the global scope, and the if
statement scope has access to all other scopes.

Reminder: Variable declarations and scope As you know, variables
declared with let and const can only ever be declared once. But there's
one exception to this rule: you may declare variables that are in
sibling scopes. For example, pay attention to the price variable in the
following code sample:

const DISCOUNT<sub>PERCENTAGE</sub> = 0.15; const product = { name:
"Black Longline T-Shirt", priceInCents: 1500, availableSizes: \["XS",
"S", "XL", "XXL"\], };

if (DISCOUNT<sub>PERCENTAGE</sub> \> 0) { const multiplier = 1 -
DISCOUNT<sub>PERCENTAGE</sub>; const price = product.priceInCents \*
multiplier; console.log(price); } else { const price =
product.priceInCents; console.log(price); }

In the case above, price is declared twice as a const variable, but the
scopes are separate. That means that they can both be declared
successfully on their own.

## Recursion

Replace Loops using Recursion Recursion is the concept that a function
can be expressed in terms of itself. To help understand this, start by
thinking about the following task: multiply the first n elements of an
array to create the product of those elements. Using a for loop, you
could do this: function multiply(arr, n) { let product = 1; for (let i =
0; i \< n; i++) { product \*= arr\[i\]; } return product; } However,
notice that multiply(arr, n) == multiply(arr, n - 1) \* arr\[n - 1\].
That means you can rewrite multiply in terms of itself and never need to
use a loop. function multiply(arr, n) { if (n \<= 0) { return 1; } else
{ return multiply(arr, n - 1) \* arr\[n - 1\]; } } The recursive version
of multiply breaks down like this. In the base case, where n \<= 0, it
returns 1. For larger values of n, it calls itself, but with n - 1. That
function call is evaluated in the same way, calling multiply again until
n \<= 0. At this point, all the functions can return and the original
multiply returns the answer. Note: Recursive functions must have a base
case when they return without calling the function again (in this
example, when n \<= 0), otherwise they can never finish executing. Write
a recursive function, sum(arr, n), that returns the sum of the first n
elements of an array arr.

## Math

Generate Random Fractions with JavaScript Random numbers are useful for
creating random behavior. JavaScript has a Math.random() function that
generates a random decimal number between 0 (inclusive) and 1
(exclusive). Thus Math.random() can return a 0 but never return a 1.
Note: Like Storing Values with the Assignment Operator, all function
calls will be resolved before the return executes, so we can return the
value of the Math.random() function. Change randomFraction to return a
random number instead of returning 0.

Generate Random Whole Numbers with JavaScript It's great that we can
generate random decimal numbers, but it's even more useful if we use it
to generate random whole numbers. Use Math.random() to generate a random
decimal. Multiply that random decimal by 20. Use another function,
Math.floor() to round the number down to its nearest whole number.
Remember that Math.random() can never quite return a 1 and, because
we're rounding down, it's impossible to actually get 20. This technique
will give us a whole number between 0 and 19. Putting everything
together, this is what our code looks like: Math.floor(Math.random() \*
20); We are calling Math.random(), multiplying the result by 20, then
passing the value to Math.floor() function to round the value down to
the nearest whole number. Use this technique to generate and return a
random whole number between 0 and 9.

Generate Random Whole Numbers within a Range Instead of generating a
random whole number between zero and a given number like we did before,
we can generate a random whole number that falls within a range of two
specific numbers. To do this, we'll define a minimum number min and a
maximum number max. Here's the formula we'll use. Take a moment to read
it and try to understand what this code is doing:
Math.floor(Math.random() \* (max - min + 1)) + min Create a function
called randomRange that takes a range myMin and myMax and returns a
random whole number that's greater than or equal to myMin, and is less
than or equal to myMax, inclusive.

## Resources

### Finish

freeCodeCamp Basic JavaScript i didn't understand recursion without loop

## Html Dom

get the element iwth the specified id:
document.getElementById(elementID) document.getElementById("demo")

The example below "finds" an HTML element (with id="demo"), and changes
the element content (innerHTML) to "Hello JavaScript":

JavaScript Can Change HTML Styles (CSS) Changing the style of an HTML
element, is a variant of changing an HTML attribute: Example
document.getElementById("demo").style.fontSize = "35px";

JavaScript Can Hide HTML Elements Hiding HTML elements can be done by
changing the display style: Example
document.getElementById("demo").style.display = "none";

``` javascript
// js get the element with the specified id:demo
document.getElementById("demo");
// js using id:demo and change html content: Hello
document.getElementById("demo").innerHTML = "Hello";
// js using id:demo and change html styles font size to 35px
document.getElementById("demo").style.fontSize = "35px";
// js using id:demo and change html styles: display to none
document.getElementById("demo").style.display = "none";
```

## JavaScript Events

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these
events. HTML Events

An HTML event can be something the browser does, or something a user
does.

Here are some examples of HTML events:

An HTML web page has finished loading An HTML input field was changed An
HTML button was clicked

Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added
to HTML elements.

With single quotes: \<element event='some JavaScript'\>

With double quotes: \<element event="some JavaScript"\>

In the following example, an onclick attribute (with code), is added to
a \<button\> element: Example \<button
onclick="document.getElementById('demo').innerHTML = Date()"\>The time
is?\</button\>

In the example above, the JavaScript code changes the content of the
element with id="demo".

In the next example, the code changes the content of its own element
(using this.innerHTML): Example \<button onclick="this.innerHTML =
Date()"\>The time is?\</button\>

JavaScript code is often several lines long. It is more common to see
event attributes calling functions: Example \<button
onclick="displayDate()"\>The time is?\</button\> Common HTML Events

Here is a list of some common HTML events: Event Description onchange An
HTML element has been changed onclick The user clicks an HTML element
onmouseover The user moves the mouse over an HTML element onmouseout The
user moves the mouse away from an HTML element onkeydown The user pushes
a keyboard key onload The browser has finished loading the page

The list is much longer: W3Schools JavaScript Reference HTML DOM Events.
JavaScript Event Handlers

Event handlers can be used to handle and verify user input, user
actions, and browser actions:

Things that should be done every time a page loads Things that should be
done when the page is closed Action that should be performed when a user
clicks a button Content that should be verified when a user inputs data
And more …

Many different methods can be used to let JavaScript work with events:

HTML event attributes can execute JavaScript code directly HTML event
attributes can call JavaScript functions You can assign your own event
handler functions to HTML elements You can prevent events from being
sent or being handled And more …

You will learn a lot more about events and event handlers in the HTML
DOM chapters. Test Yourself With Exercises Exercise:

The \<button\> element should do something when someone clicks on it.
Try to fix it!

\<button ="alert('Hello')"\>Click me.\</button\>

Start the Exercise

## JavaScript Style Guide

Always use the same coding conventions for all your JavaScript projects.

JavaScript Coding Conventions Coding conventions are style guidelines
for programming. They typically cover:

Naming and declaration rules for variables and functions. Rules for the
use of white space, indentation, and comments. Programming practices and
principles Coding conventions secure quality:

Improves code readability Make code maintenance easier Coding
conventions can be documented rules for teams to follow, or just be your
individual coding practice.

This page describes the general JavaScript code conventions used by
W3Schools. You should also read the next chapter "Best Practices", and
learn how to avoid coding pitfalls.

Variable Names At W3schools we use camelCase for identifier names
(variables and functions).

All names start with a letter.

At the bottom of this page, you will find a wider discussion about
naming rules.

firstName = "John"; lastName = "Doe";

price = 19.90; tax = 0.20;

fullPrice = price + (price \* tax); Spaces Around Operators Always put
spaces around operators ( = + - \* / ), and after commas:

Examples: let x = y + z; const myArray = \["Volvo", "Saab", "Fiat"\];
Code Indentation Always use 2 spaces for indentation of code blocks:

Functions: function toCelsius(fahrenheit) { return (5 / 9) \*
(fahrenheit - 32); } Do not use tabs (tabulators) for indentation.
Different editors interpret tabs differently.

Statement Rules General rules for simple statements:

Always end a simple statement with a semicolon. Examples: const cars =
\["Volvo", "Saab", "Fiat"\];

const person = { firstName: "John", lastName: "Doe", age: 50, eyeColor:
"blue" }; General rules for complex (compound) statements:

Put the opening bracket at the end of the first line. Use one space
before the opening bracket. Put the closing bracket on a new line,
without leading spaces. Do not end a complex statement with a semicolon.
Functions: function toCelsius(fahrenheit) { return (5 / 9) \*
(fahrenheit - 32); } Loops: for (let i = 0; i \< 5; i++) { x += i; }
Conditionals: if (time \< 20) { greeting = "Good day"; } else { greeting
= "Good evening"; } Object Rules General rules for object definitions:

Place the opening bracket on the same line as the object name. Use colon
plus one space between each property and its value. Use quotes around
string values, not around numeric values. Do not add a comma after the
last property-value pair. Place the closing bracket on a new line,
without leading spaces. Always end an object definition with a
semicolon. Example const person = { firstName: "John", lastName: "Doe",
age: 50, eyeColor: "blue" }; Short objects can be written compressed, on
one line, using spaces only between properties, like this:

const person = {firstName:"John", lastName:"Doe", age:50,
eyeColor:"blue"}; Line Length \< 80 For readability, avoid lines longer
than 80 characters.

If a JavaScript statement does not fit on one line, the best place to
break it, is after an operator or a comma.

Example document.getElementById("demo").innerHTML = "Hello Dolly.";
Naming Conventions Always use the same naming convention for all your
code. For example:

Variable and function names written as camelCase Global variables
written in UPPERCASE (We don't, but it's quite common) Constants (like
PI) written in UPPERCASE Should you use hyp-hens, camelCase, or
under<sub>scores</sub> in variable names?

This is a question programmers often discuss. The answer depends on who
you ask:

Hyphens in HTML and CSS:

HTML5 attributes can start with data- (data-quantity, data-price).

CSS uses hyphens in property-names (font-size).

Hyphens can be mistaken as subtraction attempts. Hyphens are not allowed
in JavaScript names.

Underscores:

Many programmers prefer to use underscores (date<sub>ofbirth</sub>),
especially in SQL databases.

Underscores are often used in PHP documentation.

PascalCase:

PascalCase is often preferred by C programmers.

camelCase:

camelCase is used by JavaScript itself, by jQuery, and other JavaScript
libraries.

Do not start names with a \$ sign. It will put you in conflict with many
JavaScript library names.

Loading JavaScript in HTML Use simple syntax for loading external
scripts (the type attribute is not necessary):

\<script src="myscript.js"\>\</script\> Accessing HTML Elements A
consequence of using "untidy" HTML styles, might result in JavaScript
errors.

These two JavaScript statements will produce different results:

const obj = getElementById("Demo")

const obj = getElementById("demo") If possible, use the same naming
convention (as JavaScript) in HTML.

Visit the HTML Style Guide.

File Extensions HTML files should have a .html extension (.htm is
allowed).

CSS files should have a .css extension.

JavaScript files should have a .js extension.

Use Lower Case File Names Most web servers (Apache, Unix) are case
sensitive about file names:

london.jpg cannot be accessed as London.jpg.

Other web servers (Microsoft, IIS) are not case sensitive:

london.jpg can be accessed as London.jpg or london.jpg.

If you use a mix of upper and lower case, you have to be extremely
consistent.

If you move from a case insensitive, to a case sensitive server, even
small errors can break your web site.

To avoid these problems, always use lower case file names (if possible).

Performance Coding conventions are not used by computers. Most rules
have little impact on the execution of programs.

Indentation and extra spaces are not significant in small scripts.

For code in development, readability should be preferred. Larger
production scripts should be minified.

### Writing Readable Code Thinkful

earning Objective By the end of this lesson, you will be able to
refactor code to be more readable and more efficient.

Overview At this point, you've learned several important JavaScript
concepts. You're familiar with some essential JavaScript syntax,
statements, and code-writing tools. And now, it's time to take those
skills and refine them. In this lesson, you'll learn some techniques and
best practices for writing readable code.

Key Terms Guard clause A statement that evaluates to a boolean that
determines whether or not a function should continue running As you
know, developers should aim to write code that is clear, clean, and easy
to read. And this lesson is all about helping you do that. Of course,
there are different approaches and techniques, and the advice provided
in this lesson reflects that subjectivity. None of the techniques
included here are required. However, they will improve the readability
of your code, and using them will show other developers (and potential
employers) that you're thoughtful, careful, and professional.

For more advice on how to write code well, speak with experts in the
field. Many developers have strong opinions on how to write code that is
more legible and maintainable. Gathering information from different
experts will help inform your preferences and practices.

Don't repeat yourself One important rule that you will often hear as a
developer is not to repeat yourself. In fact, don't repeat yourself is
often abbreviated to DRY, and the whole idea is often captured in the
following advice: write DRY code. Generally, this idea is used
specifically in the context of functions. Because functions allow you to
wrap up repeated code within a function, they can be particularly
helpful when it comes to writing DRY code.

However, this is only one way to think about the phrase "don't repeat
yourself." Take a look at the following data and function. Spend a few
moments reviewing it to make sure you understand what is happening. What
do you notice? Then, try running the function yourself.

const authors = \[ { id: 1, name: { firstName: "Philip", surname:
"Pullman", }, series: \["His Dark Materials", "Sally Lockhart"\], }, {
id: 2, name: { firstName: "Terry", lastName: "Pratchett", }, series:
\["Discworld", "Long Earth"\], }, \];

function getAllSeries(authors) { const result = \[\]; for (let i = 0; i
\< authors.length; i++) { for (let j = 0; j \<
authors\[i\].series.length; j++) {
result.push(authors\[i\].series\[j\]); } } return result; }

getAllSeries(authors); //\> \[ 'His Dark Materials', 'Sally Lockhart',
'Discworld', 'Long Earth' \] In the above function, there is some
duplicate code. Can you see it? The code shows authors\[i\] multiple
times.

But maybe that can be tightened up. Instead, you could assign this value
to the variable. Check it out:

function getAllSeries(authors) { const result = \[\]; for (let i = 0; i
\< authors.length; i++) { const author = authors\[i\]; for (let j = 0; j
\< author.series.length; j++) { result.push(author.series\[j\]); } }
return result; } Although you've technically made the above function a
bit longer, it's now much clearer. It also avoids using authors\[i\]
multiple times.

If you want to try out the code, you can use this REPL:

Return early Another important rule is to return early. At its most
basic level, the return-early mindset involves writing a function that
terminates or throws an error as soon as something is wrong, with the
goal of yielding the correct result—the one that you'd expect—at the end
of the function.

To better understand this idea, take a look at the following function.
This code sample expects inputted data that is similar to that authors
array from above.

function getSeriesListById(authors, id) { let selected = null; for (let
i = 0; i \< authors.length; i++) { const author = authors\[i\]; if
(author.id `=` id) selected = author; }

if (id) { if (selected) { const message = \`Series list:
\${selected.series.join(", ")}\`; return message; } else { return \[\];
} } else { return "No ID provided."; } } In the above function, the
authors array and an id are given to the function. If the id matches one
of the authors, the code returns the series for that author. Otherwise,
it returns an empty array. If no id is inputted, it returns a string at
the end saying so: No ID provided.

The above code isn't that complicated. But it can be made simpler by
returning early. Check it out:

function getSeriesListById(authors, id) { if (!id) return "No ID
provided.";

let selected = null; for (let i = 0; i \< authors.length; i++) { const
author = authors\[i\]; if (author.id `=` id) selected = author; } if
(!selected) return \[\];

return \`Series list: \${selected.series.join(", ")}\`; } In this
modified example, the function stops if there is no id inputted rather
than running despite the lack of id. In fact, when the function stops,
the same string from above, No ID provided, is returned. But you'll
notice that this happens near the beginning of the function, rather than
at the end. This means that the code below that point does not have to
run, and it is letting you know as soon as possible that there's no id
inputted.

This is sometimes referred to as a guard clause. A guard clause is a
statement that evaluates to a boolean that determines whether or not a
function should continue running. Implementing guard clauses in your
code will make your code much more efficient and easier to read.

Avoid boolean returns One final rule is to avoid boolean returns when
possible. Although this isn't always possible, you can often avoid
explicitly returning true and false by returning the expression that is
evaluating the statement.

For example, take a look at the following function. What do you notice?

function moreThanThreeAuthors(authors) { if (authors.length \> 3) {
return true; } else { return false; } } The function above just checks
if there are more than three authors in the given array. But you can
actually write a stronger, shorter function with the following:

function moreThanThreeAuthors(authors) { return authors.length \> 3; }
The conditional statement will already be evaluated to a boolean, so you
don't need to explicitly return true or false.

DRY (Don't repeat yourself) & Writing readable code

Simplify condition based functions by returning the comparison instead
of true or false explicitly

function isAdult(age){ if(age \> 17){ return true; } else { return
false; } }

function isAdult(age){ return age \> 17; }

DRY (Don't repeat yourself) & Writing readable code

const characters = \[ { id: 1, name: { firstName: "Sonic", lastname:
"Hedgehog", }, games: \["Sonic 1", "Sonic 2"\], }, { id: 2, name: {
firstName: "Lara", lastName: "Croft", }, games: \["Tomb Raider", "Tomb
Raider 2"\], }, \];

function getAllGames(characters) { const result = \[\]; for (let i = 0;
i \< characters.length; i++) { for (let j = 0; j \<
characters\[i\].games.length; j++) {
result.push(characters\[i\].games\[j\]); } } return result; }

getAllGames(characters);

function getAllGames(characters) { const result = \[\]; for (let i = 0;
i \< characters.length; i++) { const character = characters\[i\]; for
(let j = 0; j \< character.games.length; j++) {
result.push(character.games\[j\]); } } return result; }

getAllGames(characters);

## JavaScript Best Practices

Avoid global variables, avoid new, avoid ==, avoid eval()

Avoid Global Variables Minimize the use of global variables.

This includes all data types, objects, and functions.

Global variables and functions can be overwritten by other scripts.

Use local variables instead, and learn how to use closures.

Always Declare Local Variables All variables used in a function should
be declared as local variables.

Local variables must be declared with the var keyword or the let
keyword,or the const keyword, otherwise they will become global
variables.

Strict mode does not allow undeclared variables.

Declarations on Top It is a good coding practice to put all declarations
at the top of each script or function.

This will:

Give cleaner code Provide a single place to look for local variables
Make it easier to avoid unwanted (implied) global variables Reduce the
possibility of unwanted re-declarations // Declare at the beginning let
firstName, lastName, price, discount, fullPrice;

// Use later firstName = "John"; lastName = "Doe";

price = 19.90; discount = 0.10;

fullPrice = price - discount; This also goes for loop variables:

for (let i = 0; i \< 5; i++) { Initialize Variables It is a good coding
practice to initialize variables when you declare them.

This will:

Give cleaner code Provide a single place to initialize variables Avoid
undefined values // Declare and initiate at the beginning let firstName
= "", let lastName = "", let price = 0, let discount = 0, let fullPrice
= 0, const myArray = \[\], const myObject = {}; Initializing variables
provides an idea of the intended use (and intended data type).

Declare Objects with const Declaring objects with const will prevent any
accidental change of type:

Example let car = {type:"Fiat", model:"500", color:"white"}; car =
"Fiat"; // Changes object to string

const car = {type:"Fiat", model:"500", color:"white"}; car = "Fiat"; //
Not possible Declare Arrays with const Declaring arrays with const will
prevent any accidential change of type:

Example let cars = \["Saab", "Volvo", "BMW"\]; cars = 3; // Changes
array to number

const cars = \["Saab", "Volvo", "BMW"\]; cars = 3; // Not possible Don't
Use new Object() Use "" instead of new String() Use 0 instead of new
Number() Use false instead of new Boolean() Use {} instead of new
Object() Use \[\] instead of new Array() Use *()* instead of new
RegExp() Use function (){} instead of new Function() Example let x1 =
""; // new primitive string let x2 = 0; // new primitive number let x3 =
false; // new primitive boolean const x4 = {}; // new object const x5 =
\[\]; // new array object const x6 = *()*; // new regexp object const x7
= function(){}; // new function object Beware of Automatic Type
Conversions JavaScript is loosely typed.

A variable can contain all data types.

A variable can change its data type:

Example let x = "Hello"; // typeof x is a string x = 5; // changes
typeof x to a number Beware that numbers can accidentally be converted
to strings or NaN (Not a Number).

When doing mathematical operations, JavaScript can convert numbers to
strings:

Example let x = 5 + 7; // x.valueOf() is 12, typeof x is a number let x
= 5 + "7"; // x.valueOf() is 57, typeof x is a string let x = "5" + 7;
// x.valueOf() is 57, typeof x is a string let x = 5 - 7; // x.valueOf()
is -2, typeof x is a number let x = 5 - "7"; // x.valueOf() is -2,
typeof x is a number let x = "5" - 7; // x.valueOf() is -2, typeof x is
a number let x = 5 - "x"; // x.valueOf() is NaN, typeof x is a number
Subtracting a string from a string, does not generate an error but
returns NaN (Not a Number):

Example "Hello" - "Dolly" // returns NaN Use `=` Comparison The ==
comparison operator always converts (to matching types) before
comparison.

The `=` operator forces comparison of values and type:

Example 0 == ""; // true 1 == "1"; // true 1 == true; // true

0 `=` ""; // false 1 `=` "1"; // false 1 `=` true; // false Use
Parameter Defaults If a function is called with a missing argument, the
value of the missing argument is set to undefined.

Undefined values can break your code. It is a good habit to assign
default values to arguments.

Example function myFunction(x, y) { if (y `=` undefined) { y = 0; } }
ECMAScript 2015 allows default parameters in the function definition:

function (a=1, b=1) { ***function code*** } Read more about function
parameters and arguments at Function Parameters

End Your Switches with Defaults Always end your switch statements with a
default. Even if you think there is no need for it.

Example switch (new Date().getDay()) { case 0: day = "Sunday"; break;
case 1: day = "Monday"; break; case 2: day = "Tuesday"; break; case 3:
day = "Wednesday"; break; case 4: day = "Thursday"; break; case 5: day =
"Friday"; break; case 6: day = "Saturday"; break; default: day =
"Unknown"; } Avoid Number, String, and Boolean as Objects Always treat
numbers, strings, or booleans as primitive values. Not as objects.

Declaring these types as objects, slows down execution speed, and
produces nasty side effects:

Example let x = "John"; let y = new String("John"); (x `=` y) // is
false because x is a string and y is an object. Or even worse:

Example let x = new String("John"); let y = new String("John"); (x == y)
// is false because you cannot compare objects. Avoid Using eval() The
eval() function is used to run text as code. In almost all cases, it
should not be necessary to use it.

Because it allows arbitrary code to be run, it also represents a
security problem.

## JavaScript Common Mistakes

This chapter points out some common JavaScript mistakes.

Accidentally Using the Assignment Operator JavaScript programs may
generate unexpected results if a programmer accidentally uses an
assignment operator (`), instead of a comparison operator (=`) in an if
statement.

This if statement returns false (as expected) because x is not equal to
10:

let x = 0; if (x == 10) This if statement returns true (maybe not as
expected), because 10 is true:

let x = 0; if (x = 10) This if statement returns false (maybe not as
expected), because 0 is false:

let x = 0; if (x = 0) An assignment always returns the value of the
assignment.

Expecting Loose Comparison In regular comparison, data type does not
matter. This if statement returns true:

let x = 10; let y = "10"; if (x == y) In strict comparison, data type
does matter. This if statement returns false:

let x = 10; let y = "10"; if (x `=` y) It is a common mistake to forget
that switch statements use strict comparison:

This case switch will display an alert:

let x = 10; switch(x) { case 10: alert("Hello"); } This case switch will
not display an alert:

let x = 10; switch(x) { case "10": alert("Hello"); } Confusing Addition
& Concatenation Addition is about adding numbers.

Concatenation is about adding strings.

In JavaScript both operations use the same + operator.

Because of this, adding a number as a number will produce a different
result from adding a number as a string:

let x = 10; x = 10 + 5; // Now x is 15

let y = 10; y += "5"; // Now y is "105" When adding two variables, it
can be difficult to anticipate the result:

let x = 10; let y = 5; let z = x + y; // Now z is 15

let x = 10; let y = "5"; let z = x + y; // Now z is "105"
Misunderstanding Floats All numbers in JavaScript are stored as 64-bits
Floating point numbers (Floats).

All programming languages, including JavaScript, have difficulties with
precise floating point values:

let x = 0.1; let y = 0.2; let z = x + y // the result in z will not be
0.3 To solve the problem above, it helps to multiply and divide:

Example let z = (x \* 10 + y \* 10) / 10; // z will be 0.3 Breaking a
JavaScript String JavaScript will allow you to break a statement into
two lines:

Example 1 let x = "Hello World!"; But, breaking a statement in the
middle of a string will not work:

Example 2 let x = "Hello World!"; You must use a "backslash" if you must
break a statement in a string:

Example 3 let x = "Hello \\ World!"; Misplacing Semicolon Because of a
misplaced semicolon, this code block will execute regardless of the
value of x:

if (x == 19); { // code block } Breaking a Return Statement It is a
default JavaScript behavior to close a statement automatically at the
end of a line.

Because of this, these two examples will return the same result:

Example 1 function myFunction(a) { let power = 10 return a \* power }
Example 2 function myFunction(a) { let power = 10; return a \* power; }
JavaScript will also allow you to break a statement into two lines.

Because of this, example 3 will also return the same result:

Example 3 function myFunction(a) { let power = 10; return a \* power; }
But, what will happen if you break the return statement in two lines
like this:

Example 4 function myFunction(a) { let power = 10; return a \* power; }
The function will return undefined!

Why? Because JavaScript thought you meant:

Example 5 function myFunction(a) { let power = 10; return; a \* power; }
Explanation If a statement is incomplete like:

let JavaScript will try to complete the statement by reading the next
line:

power = 10; But since this statement is complete:

return JavaScript will automatically close it like this:

return; This happens because closing (ending) statements with semicolon
is optional in JavaScript.

JavaScript will close the return statement at the end of the line,
because it is a complete statement.

Never break a return statement.

Accessing Arrays with Named Indexes Many programming languages support
arrays with named indexes.

Arrays with named indexes are called associative arrays (or hashes).

JavaScript does not support arrays with named indexes.

In JavaScript, arrays use numbered indexes:

Example const person = \[\]; person\[0\] = "John"; person\[1\] = "Doe";
person\[2\] = 46; person.length; // person.length will return 3
person\[0\]; // person\[0\] will return "John" In JavaScript, objects
use named indexes.

If you use a named index, when accessing an array, JavaScript will
redefine the array to a standard object.

After the automatic redefinition, array methods and properties will
produce undefined or incorrect results:

Example: const person = \[\]; person\["firstName"\] = "John";
person\["lastName"\] = "Doe"; person\["age"\] = 46; person.length; //
person.length will return 0 person\[0\]; // person\[0\] will return
undefined Ending Definitions with a Comma Trailing commas in object and
array definition are legal in ECMAScript 5.

Object Example: person = {firstName:"John", lastName:"Doe", age:46,}
Array Example: points = \[40, 100, 1, 5, 25, 10,\]; WARNING !!

Internet Explorer 8 will crash.

JSON does not allow trailing commas.

JSON: person = {"firstName":"John", "lastName":"Doe", "age":46} JSON:
points = \[40, 100, 1, 5, 25, 10\]; Undefined is Not Null JavaScript
objects, variables, properties, and methods can be undefined.

In addition, empty JavaScript objects can have the value null.

This can make it a little bit difficult to test if an object is empty.

You can test if an object exists by testing if the type is undefined:

Example: if (typeof myObj `=` "undefined") But you cannot test if an
object is null, because this will throw an error if the object is
undefined:

Incorrect: if (myObj `=` null) To solve this problem, you must test if
an object is not null, and not undefined.

But this can still throw an error:

Incorrect: if (myObj !== null && typeof myObj !== "undefined") Because
of this, you must test for not undefined before you can test for not
null:

Correct: if (typeof myObj !== "undefined" && myObj !== null)

## JavaScript Performance

How to speed up your JavaScript code.

Reduce Activity in Loops Loops are often used in programming.

Each statement in a loop, including the for statement, is executed for
each iteration of the loop.

Statements or assignments that can be placed outside the loop will make
the loop run faster.

Bad: for (let i = 0; i \< arr.length; i++) { Better Code: let l =
arr.length; for (let i = 0; i \< l; i++) { The bad code accesses the
length property of an array each time the loop is iterated.

The better code accesses the length property outside the loop and makes
the loop run faster.

Reduce DOM Access Accessing the HTML DOM is very slow, compared to other
JavaScript statements.

If you expect to access a DOM element several times, access it once, and
use it as a local variable:

Example const obj = document.getElementById("demo"); obj.innerHTML =
"Hello"; Reduce DOM Size Keep the number of elements in the HTML DOM
small.

This will always improve page loading, and speed up rendering (page
display), especially on smaller devices.

Every attempt to search the DOM (like getElementsByTagName) will benefit
from a smaller DOM.

Avoid Unnecessary Variables Don't create new variables if you don't plan
to save values.

Often you can replace code like this:

let fullName = firstName + " " + lastName;
document.getElementById("demo").innerHTML = fullName; With this:

document.getElementById("demo").innerHTML = firstName + " " + lastName;
Delay JavaScript Loading Putting your scripts at the bottom of the page
body lets the browser load the page first.

While a script is downloading, the browser will not start any other
downloads. In addition all parsing and rendering activity might be
blocked.

The HTTP specification defines that browsers should not download more
than two components in parallel.

An alternative is to use defer="true" in the script tag. The defer
attribute specifies that the script should be executed after the page
has finished parsing, but it only works for external scripts.

If possible, you can add your script to the page by code, after the page
has loaded:

Example \<script\> window.onload = function() { const element =
document.createElement("script"); element.src = "myScript.js";
document.body.appendChild(element); }; \</script\> Avoid Using with
Avoid using the with keyword. It has a negative effect on speed. It also
clutters up JavaScript scopes.

The with keyword is not allowed in strict mode.

## Unsorted Js

console.log() prints to the console Data is printed, or logged, to the
console, a panel that displays messages, with console.log().
console.log("hello")

window.alert(); creates a popup window.alert("hello");

Built-in objects, including Math, are collections of methods and
properties that JavaScript provides.

REPL stand for Read-eval-print loop an interactive computer programming
environment that lets you perform basic tasks

Order of operations Also called operator precedence, a collection of
rules that govern the order in which operators are evaluated Parentheses
Exponents Multiplication Division Addition Subtraction

Truthy values Values that an if statement will treat as true !! turns
anything to a boolean Falsy values Values that an if statement will
treat as false // Values that evaluate to \`false\` false; // \`false\`
itself ""; // Empty string 0; // Zero null; undefined; NaN; // Not a
number

Tracing The process of following values through a program

conditional statements An if statement checks a condition and will
execute a task if that condition evaluates to true. if…else statements
make binary decisions and execute different code blocks based on a
provided condition. We can add more conditions using else if statements.
Comparison operators, including \<, \>, \<=, \>=, `=`, and !== can
compare two values. The logical and operator, &&, or “and”, checks if
both provided expressions are truthy. The logical operator \|\|, or
“or”, checks if either provided expression is truthy. The bang operator,
!, switches the truthiness and falsiness of a value. The ternary
operator is shorthand to simplify concise if…else statements. A switch
statement can be used to simplify the process of writing multiple else
if statements. The break keyword stops the remaining cases from being
checked and executed in a switch statement.

### JavaScript Where To

The \<script\> Tag

In HTML, JavaScript code is inserted between \<script\> and \</script\>
tags. Example \<script\> document.getElementById("demo").innerHTML = "My
First JavaScript"; \</script\>

Old JavaScript examples may use a type attribute: \<script
type="text/javascript"\>. The type attribute is not required. JavaScript
is the default scripting language in HTML. JavaScript Functions and
Events

A JavaScript function is a block of JavaScript code, that can be
executed when "called" for.

For example, a function can be called when an event occurs, like when
the user clicks a button.

You will learn much more about functions and events in later chapters.
JavaScript in \<head\> or \<body\>

You can place any number of scripts in an HTML document.

Scripts can be placed in the \<body\>, or in the \<head\> section of an
HTML page, or in both. JavaScript in \<head\>

In this example, a JavaScript function is placed in the \<head\> section
of an HTML page.

The function is invoked (called) when a button is clicked: Example
\<!DOCTYPE html\> \<html\> \<head\> \<script\> function myFunction() {
document.getElementById("demo").innerHTML = "Paragraph changed."; }
\</script\> \</head\> \<body\>

\<h2\>Demo JavaScript in Head\</h2\>

\<p id="demo"\>A Paragraph\</p\> \<button type="button"
onclick="myFunction()"\>Try it\</button\>

\</body\> \</html\> JavaScript in \<body\>

In this example, a JavaScript function is placed in the \<body\> section
of an HTML page.

The function is invoked (called) when a button is clicked: Example
\<!DOCTYPE html\> \<html\> \<body\>

\<h2\>Demo JavaScript in Body\</h2\>

\<p id="demo"\>A Paragraph\</p\>

\<button type="button" onclick="myFunction()"\>Try it\</button\>

\<script\> function myFunction() {
document.getElementById("demo").innerHTML = "Paragraph changed."; }
\</script\>

\</body\> \</html\>

Placing scripts at the bottom of the \<body\> element improves the
display speed, because script interpretation slows down the display.
External JavaScript

Scripts can also be placed in external files: External file: myScript.js
function myFunction() { document.getElementById("demo").innerHTML =
"Paragraph changed."; }

External scripts are practical when the same code is used in many
different web pages.

JavaScript files have the file extension .js.

To use an external script, put the name of the script file in the src
(source) attribute of a \<script\> tag: Example \<script
src="myScript.js"\>\</script\>

You can place an external script reference in \<head\> or \<body\> as
you like.

The script will behave as if it was located exactly where the \<script\>
tag is located.

External scripts cannot contain \<script\> tags. External JavaScript
Advantages

Placing scripts in external files has some advantages:

It separates HTML and code It makes HTML and JavaScript easier to read
and maintain Cached JavaScript files can speed up page loads

To add several script files to one page - use several script tags:
Example \<script src="myScript1.js"\>\</script\> \<script
src="myScript2.js"\>\</script\> External References

An external script can be referenced in 3 different ways:

With a full URL (a full web address) With a file path (like *js*)
Without any path

This example uses a full URL to link to myScript.js: Example \<script
src="<https://www.w3schools.com/js/myScript.js>"\>\</script\>

This example uses a file path to link to myScript.js: Example \<script
src="/js/myScript.js"\>\</script\>

This example uses no path to link to myScript.js: Example \<script
src="myScript.js"\>\</script\>

### JavaScript Output

JavaScript Display Possibilities

JavaScript can "display" data in different ways:

Writing into an HTML element, using innerHTML. Writing into the HTML
output using document.write(). Writing into an alert box, using
window.alert(). Writing into the browser console, using console.log().

Using innerHTML

To access an HTML element, JavaScript can use the
document.getElementById(id) method.

The id attribute defines the HTML element. The innerHTML property
defines the HTML content: Example \<!DOCTYPE html\> \<html\> \<body\>

\<h1\>My First Web Page\</h1\> \<p\>My First Paragraph\</p\>

\<p id="demo"\>\</p\>

\<script\> document.getElementById("demo").innerHTML = 5 + 6;
\</script\>

\</body\> \</html\>

Changing the innerHTML property of an HTML element is a common way to
display data in HTML. Using document.write()

For testing purposes, it is convenient to use document.write(): Example
\<!DOCTYPE html\> \<html\> \<body\>

\<h1\>My First Web Page\</h1\> \<p\>My first paragraph.\</p\>

\<script\> document.write(5 + 6); \</script\>

\</body\> \</html\>

Using document.write() after an HTML document is loaded, will delete all
existing HTML: Example \<!DOCTYPE html\> \<html\> \<body\>

\<h1\>My First Web Page\</h1\> \<p\>My first paragraph.\</p\>

\<button type="button" onclick="document.write(5 + 6)"\>Try
it\</button\>

\</body\> \</html\>

The document.write() method should only be used for testing. Using
window.alert()

You can use an alert box to display data: Example \<!DOCTYPE html\>
\<html\> \<body\>

\<h1\>My First Web Page\</h1\> \<p\>My first paragraph.\</p\>

\<script\> window.alert(5 + 6); \</script\>

\</body\> \</html\>

You can skip the window keyword.

In JavaScript, the window object is the global scope object, that means
that variables, properties, and methods by default belong to the window
object. This also means that specifying the window keyword is optional:
Example \<!DOCTYPE html\> \<html\> \<body\>

\<h1\>My First Web Page\</h1\> \<p\>My first paragraph.\</p\>

\<script\> alert(5 + 6); \</script\>

\</body\> \</html\> Using console.log()

For debugging purposes, you can call the console.log() method in the
browser to display data.

You will learn more about debugging in a later chapter. Example
\<!DOCTYPE html\> \<html\> \<body\>

\<script\> console.log(5 + 6); \</script\>

\</body\> \</html\> JavaScript Print

JavaScript does not have any print object or print methods.

You cannot access output devices from JavaScript.

The only exception is that you can call the window.print() method in the
browser to print the content of the current window. Example \<!DOCTYPE
html\> \<html\> \<body\>

\<button onclick="window.print()"\>Print this page\</button\>

\</body\> \</html\>

### Error Types Thinkful

1. Runtime errors

    errorType: description of the error SyntaxError: function statement
    requires a name

2. Reference errors

    Reference error - An error that occurs when some variable being
    referenced doesn't exist or can't be accessed

    In console.log statement the variable customerName is misspelled

    A reference error tells you that some variable being referenced
    doesn't exist. You can fix this kind of error by finding the
    offending reference and checking for the correct name.

    But a ReferenceError could also surface if the variable cannot be
    accessed at all.

    In the above example, the result variable does exist, but it exists
    only inside the addSalesTax() function. Attempting to access that
    variable outside of that function would lead to a ReferenceError.
    (This is because of a concept called scope, which you'll learn about
    later in this module.)

    ``` javascript
    // reference error caused by misspelling variable name
    const customerName = "Alfie Lee";
    // customerName is mis-spelled
    console.log(customrName); // returns ReferenceError: customrName is not defined

    // reference error caused variable can't be accessed
    function addSalesTax(total, salesTax) { //func takes parameters total and salesTax
        let result = total * (1 + salesTax); // declare result asign total times (salesTax plus one)
        return result; // return results
    }
    // trying print result but result but result only exist is local scope of function
    console.log(result); //returns ReferenceError: result is not defined
    ```

3. Syntax errors

    Syntax error - An error that occurs when some part of the predefined
    JavaScript syntax is being used incorrectly

    A syntax error will occur when some part of the predefined
    JavaScript syntax is used incorrectly, such as a character is used
    twice or not used at all. These errors are common for developers due
    to the simple fact that coding uses many symbols and characters that
    people don't otherwise use. For instance, because curly brackets {}
    are unusual in regular typing, it can be easy to forget one.

    Take a look at the following code. Can you find what's missing?

    function printWelcome () { console.log("Welcome to our store!"; }
    Above, you'll see that the console.log() statement is missing a
    closing parenthesis ). The error that would surface because of the
    above code would be as follows:

    SyntaxError: missing ) after argument list Although that message is
    fairly straightforward, it often isn't that simple. It can be
    challenging to actually resolve a SyntaxError with longer, more
    complex code. In the case of a SyntaxError, you often just need to
    look through your code patiently and carefully for the missing or
    extra symbol.

    Correctly indenting your code and using a code formatter can be
    useful for identifying (and preventing) issues like this. For
    example, take a look at the following code.

    function openInstructions (weather, temperatureInCelsius) { if
    (weather && temperatureInCelsius) { if (weather `=` "sunny") { if
    (temperatureInCelsius \> 20) { return "Set up the patio and put out
    umbrellas. Open indoor windows."; } else { return "Set up the
    patios, umbrellas optional. Open indoor windows."; } } else if
    (weather `=` "rainy") { if (temperatureInCelsius \> 10) { return
    "Open indoor windows slightly."; } else { return "Keep windows
    closed." } } } } else { return "Please set the \`weather\` and
    \`temperatureInCelsius\` variables."; } }

    openInstructions("sunny", 18); If you were to run the above code,
    you would receive this message in the console:

    SyntaxError: expected expression, got '}' That isn't very helpful,
    and you'd have to do the legwork of resolving the issue. This is one
    of the many reasons that it's important to write your code legibly.

4. Type errors

    Type error - An error that occurs when you misuse a data type in
    JavaScript, meaning that an operation can't be performed

    And finally, you'll learn about the TypeError. A type error will
    occur when you misuse a data type in JavaScript, meaning that an
    operation can't be performed. One of the most common ways that this
    error will occur is through a situation like this:

    price.trim(); //\> TypeError: price.trim is not a function As it
    turns out, the trim() function, when called on a string, removes
    extra whitespace from the beginning and the end of that string. So
    in this case, why would price.trim() not be a function? Well, this
    error is likely telling you that price isn't actually a string.

    To better understand what's going on, take a look at the whole
    picture:

    let price = 9.99; price.trim(); //\> TypeError: price.trim is not a
    function You might expect this error to tell you that price isn't
    the right data type, rather than telling you that trim() isn't a
    function. To better understand why the error is described the way it
    is, try running the following code:

    let price = 9.99; console.log(price.trim); //\> undefined You may be
    surprised to find that calling trim as a property on price doesn't
    fail—instead, it returns an undefined. But when you try to invoke
    the undefined property, that is when you get your error.

5. Silent errors

    Silent error - An error that doesn't immediately surface when the
    code is run

    The three errors described above are caught and revealed to you when
    you run your JavaScript code. However, it's also possible for errors
    to occur as you are writing code but not immediately surface when
    you run it. This type of error is called a silent error.

    For example, take a look at the following code. Do you see any
    problems?

    function formatPrice(priceInCents) { let formattedPrice = "\$" +
    (priceInCents / 100).setFixed(2); return formattedPrice; } You may
    not notice any issues with this code right off the bat. And even
    when you run this code sample, no errors will surface. It is only
    when you invoke the function that you will see the error:

    TypeError: (priceInCents / 100).setFixed is not a function In this
    case, the function uses setFixed(), which is not a function, instead
    of toFixed(), which is a function. When working with complex
    applications with multiple functions, you'll need to be aware of
    silent errors like this one.

### References Thinkful

Primitive data type Also called a primitive or a simple data type, a
data type containing variables that store values Reference data type
Also called a reference or a complex data type, a data type containing
variables that store addresses to locations in memory

Primitive data types JavaScript has several data types that are passed
by value. These are often called primitive data types, or simply
primitives, and you've already learned a bit about them! Primitive data
types in JavaScript include strings, numbers, and booleans, as well as
null and undefined. When a primitive data type is assigned to a
variable, that variable gets its own copy.

Take a look at the following line of code:

const title = "Mort"; In this example, the variable title contains the
string "Mort". If you reassign the value contained by title to another
variable, such as name, both variables will contain their own copy of
that value. You can see this below.

let title = "Mort"; const name = title; title = "Equal Rites";
console.log(title, name); //\> "Equal Rites", "Mort" The above code is
very important. Although it may seem obvious, you should take a moment
to understand what's happening here. When title is reassigned to "Equal
Rites", notice that the name variable still holds its own copy of
"Mort".

Now, take a look at another example. As you read over this, what do you
expect to be logged?

let price = 1000; let salePrice = price; salePrice -= 100;
console.log(price, salePrice); //\> 1000 900 In the code above, the
price variable will still be the number 1000, while the salePrice
variable will be 900. Despite the modification of salePrice, price
retains its own copy of the value 1000.

Reference data types But there's another kind of data type: reference
data types. Reference data types, sometimes just called references, in
JavaScript include functions, objects, and arrays. When a reference data
type is assigned to a variable, the variable will contain a reference
(also called a pointer) to the data.

Take a look at the following example. What do you expect to happen here?

const book = { title: "Mort", author: "Terry Pratchett" }; const mort =
book; book.price = 789; console.log(mort); //\> { title: "Mort", author:
"Terry Pratchett", price: 789 } Are you surprised by the result? Both
the book variable and the mort variable point toward the same reference.
That means that if you modify the object through one variable, the other
variable will have that same modification.

This is further illustrated by the following two examples. Here's the
first:

const author = {}; const book = {}; console.log(author `=` book); //\>
false In the above console.log() statement, two empty objects, author
and book, are compared with one another. When the `=` sign is used, it
compares these objects' references.

These objects may look the same. However, the statement resolves to
false. That is because author and book each store their own references
to different objects.

Now, check out this example:

const sourcery = { title: "Sourcery", author: "Terry Pratchett" }; const
favoriteBook = sourcery; console.log(sourcery `=` favoriteBook); //\>
true In the above console.log() statement, sourcery and favoriteBook
contain references to the same object. When the `=` sign is used, it
compares these references and resolves to true.

This works the same way for arrays, as well. Take a look:

const books = \["Mort", "Sourcery", "Equal Rites"\]; const series =
books; series.push("Guards! Guards!"); console.log(books); //\> \[
"Mort", "Sourcery", "Equal Rites", "Guards! Guards!" \] In the above
example, push() changes the array to include a new title. This mutates
the original array, which both books and series are pointing toward.

Note: In the examples above, const is used instead of let to store an
array or object. And yet, the values inside of these arrays and objects
can be changed. Ultimately, const only stops reassignment, without
changing the values inside of the reference itself (in other words, the
array or object).