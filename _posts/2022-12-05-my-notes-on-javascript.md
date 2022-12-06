---
layout: post
title: My Web Development Notes 16
subtitle: 
categories: Making-a-Website-Responsive
tags: [JS]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

<Strong>There we gooooo</Strong>


```JavaScript
console.log("this message gets printed to the console"); // this is a comment
/*
all
of
this
is
a
comment
WOOOOAAW
*/
```

Data Types:
<ul>
    <li>
    Primitive
        <ul>
        <li>Number</li>
        <li>String</li>
        <li>Boolean</li>
        <li>Null</li>
        <li>Undefined: Means the value doesn't exist.</li>
        <li>Symbol</li>
        </ul>
    </li>
    <li>Object: Collections of data.</li>
</ul>

Operators:
<ul>
    <li>Addition: +</li>
    <li>Subtraction: -</li>
    <li>Multiplication: *</li>
    <li>Division: /</li>
    <li>Remainder: %</li>
    <li>String Concatenation: "string" + "string"</li>
    <li>Dot: . (used for reaching the properties or applying methods)</li>
    <li>Assignment: += (-=, *=, /=) </li>
    <li>Incrementation: ++ (--)</li>
    <li>typeof</li>
</ul>

Properties:
<ul>
    <li>
    String:
    <li>.length</li>
    </li>
</ul>

Methods:
<ul>
    <li>
    String:
        <li>.toUpperCase()</li>
        <li>.startsWith()</li>
        <li>.trim()</li>
    </li>
    <li>
    console:
        <li>log</li>
    </li>
     <li>
    Math:
        <li>.floor()</li>
        <li>.random()</li>
        <li>.ceil()</li>
    </li>
    <li>
    Number:
        <li>.isInteger()</li>
    </li>
</ul>

Objects:
<ul>
    <li>console</li>
    <li>Math</li>
    <li>Number</li>
</ul>


Variables:

```JavaScript
var name = "DONAT"; 
let name = "THEONAT"; // a different value can be assigned to name later
let name; // name variable is undefined
const name = "LİMONATA" // name is constant and can't be changed
```

String Interpolation:

```JavaScript
var name = "DONAT";
console.log(`Hilarious people tend to call me ${name} sometimes.`);
// Backticks are used for string literal and they can be achieved by pressing alt and comma on my keyboard.
```

Conditionals:

```JavaScript
let number = 1;
if (number === 15032002>) {
    // this executes
} else if (number >= 18052002>) {
    // this executes
} else {
    // this executes
}
```

Falsy Values: The values that aren't boolean in type but are evaluted as false inside of an if condition.
<ul>
    <li>0</li>
    <li>""</li>
    <li>null</li>
    <li>undefined</li>
    <li>NaN</li>
</ul>

Short-Circuit Evaluation: 

```JavaScript
let input = "";
let name = input || "Onat"; // this code assignes the truthy value to the name variable, starts checking from the left hand side.
```
Ternary Operator: 

```JavaScript
let condition = true;
condition ? console.log("Condition is true") : console.log("Condition is false");
```

Switch:

```JavaScript
let number = 3;
switch(number) {
    case 1:
        console.log("Number is 1");
        break;
    case 2: 
    console.log("Number is 2");
        break;
    default:
        console.log("Number isn't 1 or 2");
        break;
}
```

Functions:

```JavaScript
const alive = true;
function myFunction() {
    while (alive) { // haven't covered loops yet but it was a matter of life and death
        beAwsome(); // another function that will be defined in the near future
    }
}

function beAwsome(howManyTimes = 10) { // 10 is the default parameter
    console.log(`I'm ${howManyTimes} many times awsome today`);
}

// if return value of a function isn't specified, it returns undefined

const variable = function(parameter) {

} // can later be called as variable(parameter)

const variable = (parameter1, parameter2) => {
    // multiple lines
    // of code
} 

const variable = parameter1 => parameter1 * 5;
```






