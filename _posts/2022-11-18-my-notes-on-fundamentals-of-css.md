---
layout: post
title: My Web Development Notes 7
subtitle: 
categories: Fundamentals-Of-CSS
tags: [Web, Html, Css, Js]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- There are (at least) two different ways of writing CSS:
- <p id="p1">CSS ruleset: Written as a seperate CSS file</p>.
```CSS
p {
    color:red;
}
```

- CSS inline style: Written inside of an HTML file.
```HTML
<p style='color: red;'>SUUUP</p>
```

- internal stylesheet: Helps affecting multiple elements w/o adding the style to all one by one.
```HTML
<head>
    <style>
        p {
            font-size: 15px;
        }
    </style>
</head>
```

- link element: connects the seperate CSS file to the HTML file to apply the visual effects. Placed inside of the head element.

```HTML
<head>
    <link href="path to the css file" rel="stylesheet"/>
</head>
```

- rel attribute: It defines the relation between this CSS file with the HTML file. In this case, we are providing a stylesheet.

- When we write <a href="p1">such code</a>, it is applied to all of the paragraphs in our page.
- universal selector: Helps us select every element regarless of their type.
```CSS
* {
    color:red;
}
```
- class attribute: Another way of grouping elements, like using their types, and adding CSS effects on them. It is possible to add an element to couple of different groups.

```HTML
<button class="freaking awsome">I'M AN AWSOME BUTTON</button>
```

```CSS
.freaking {
    color:red;
}

.awsome {
    font-size: 20px;
}
```

- If id is used in the CSS file instead of the class, it is referred with a # instead of a . before it.

- Elements can also be affected by CSS with their attributes, meaning we can apply a certain style to the elements that contain a certain attribute.
```CSS
[src] {
    color: blue;
}
```

- This method can also be extended to specifying the value of the attribute:
```CSS
video[src*="dog"] {
    width: 100px;
}
```

- Putting * before = means any video element that includes the word "dog" inside of it's src value.





