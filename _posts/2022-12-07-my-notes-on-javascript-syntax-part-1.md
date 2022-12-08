---
layout: post
title: My Web Development Notes 16
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
