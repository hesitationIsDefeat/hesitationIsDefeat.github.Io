---
layout: post
title: My Web Development Notes 17
subtitle: 
categories: Making-a-Website-Responsive
tags: [JS]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

Arrays:

```JavaScript
let myArray = ["str", 12, true, undefined]; // arrays are ordered, can take values of different types, indexing starts at 0
let myMutableArray = []; // contents of this array can be changed as well as the arrays itself
const myMutableArray2 = []; // contents of this array can be changed but the array itself remains constant
```

Methods:
<ul>
    <li>.length</li>
    <li>.push(item1, item2): adds the given items to the end of the array</li>
    <li>.pop(): removes the last item of the array</li>
    <li>.shift(): removes and returns the first item on the array</li>
    <li>.unshift(item): adds the input to the first item on the array</li>
    <li>.slice(index1, index2): returns an array from the item at index1 up to the item at the index index2-1</li>
    <li>.indexOf(item)</li>
    <li>.length (this is a property)</li>
    <li>.join()</li>
    <li>.splice(index, number of indices, string to replace with)</li>
    <li>.includes(element)</li>
</ul>

Loops:

```JavaScript
for (let i = 0; i <= 10; i++>) {
    console.log(i);
}

const myArray = ["myElement1", "myElement2", "IAmVeryCreative"];
for (const element of myArray) {
    if (element !== "IAmVeryCreative") {
        continue;
    } else console.log(element);
}

let i = 0;
while (i < 5) {
    console.log(i);
    i ++;
}

let i = 0;
do {
console.log(i);
    i ++;
} while (i < 5);
```

Objects:

```JavaScript
let myObject = {
    prop1: 12,
    prop2: "waow",
    "prop three": true
    doSomething (input) {
        console.log("Did something!");
    }
};

console.log(myObject.prop2);
console.log(myObject["prop1"]);

myObject.newProp = "this"; // if the newProp already exists, it is changed. Otherwise, it is created

delete myObject.newProp;
```

This, Getters and Setters:

```JavaScript
const meAsSomoneElse = {
    _name: "Pancake Kid", // this naming convention is for the values we would like to keep private
    _cutenessPercentage: 100,
    actNormal() {
        console.log(`I'm ${this.name} and I tend to drink water just to feel full thus I won't consume any chocolate in NSD`); // this keyword allows us to acces the values of the specific object inside the object declaration
    },
    get name() {
        return this.name;
    },
    set cutenessPercentage(input) {
        if (typeof input === `number`) this._cutenessPercentage = input;
    } // we first check if the input is of type "number" before reassigning it since we would keep the " _cutenessPercentage" value as a number
}
meAsSomoneElse.name; // can be accessed this way, as a property
meAsSomoneElse.cutenessPercentage = 110; // this is correct sytnax of inputting since it is not a function 
```

Factory Functions (FINALLY SOME OOP):

```JavaScript
const myFactory = (name, health, stamina, mana, weapon) => { 
    return { // old way
        name: name,
        health: health,
        stamina: stamina,
        mana: mana,
        weapon: weapon
    }
};

const pyromancer = myFactory("Flame Boi", 100, 40, 60, "Parting Flame");

const myFactory2 = (name, health, stamina, mana, weapon) => { 
    return { // this is the way
        name,
        health,
        stamina,
        mana,
        weapon
    }
};

const { name } = pyromancer; // this is called "destructed asignment" and it extracts the value named "name" and saves it as a variable
```

Bult-in Methods:
<ul>
    <li>Object.keys(object1)</li>
    <li>Object.entries(object2)</li>
    <li>Object.assign(target, source)</li>
</ul>

```JavaScript
const aFunctionWithAnExtremelyLongNameForNoReasonWhatsoever = () => {

}
const shortName = aFunctionWithAnExtremelyLongNameForNoReasonWhatsoever; // this way, we can invoke this disturbingly named function with a shorter name
```

Iterators:

```JavaScript
const myArray = [1, 2, 3];
myArray.forEach(number => console.log(number)); // iterates through the whole array and executes a certain action for every element
const myArray2 = myArray.map(num => num * 5); // iterates through the whole array and returns a new array by applying a certain action on every element
const myArray3 = myArray.filter(num => num < 3) // // iterates through the whole array and returns a new array by applying a certain filter

const greaterThan2 = myArray.findIndex(num => num > 2); // returns the index of the first element that meets the given condition
const sum = myArray.reduce((first, second) => {
    return first + second;
}, 20); // I know what it does so I won't bother with explaining it, 20 is an extra argument and defines the first value of the first value
const var = myArray.some(num => num > 1); // returns true if some numbers in the array are greater than 1
const var2 = myArray.every(num => num > 1); // returns true if all numbers in the array are greater than 1
```
Error Types:

<ul>
    <li>TypeError</li>
    <li>ReferenceError</li>
    <li>SyntaxError</li>
</ul>

Sort Method:

```JavaScript
const numbers = [1, 5, 3];
console.log(numbers.sort((a,b) => {
    if (a > b) return -1; // places a before b
    else if (a <> b) return 1; // places a after b
    else return 0;
}))
```