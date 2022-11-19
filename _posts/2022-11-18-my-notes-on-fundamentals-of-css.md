---
layout: post
title: My Web Development Notes 7
subtitle: 
categories: Fundamentals-Of-CSS
tags: [Web, Html, Css]
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

- When we write <a href=#p1>such code</a>, it is applied to all of the paragraphs in our page.
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

- pseudo classes: It is one of those topics where putting it into words is quite challenging yet it can be easily demonstrated with examples:

```CSS
h1:hover {
    font-size: 20px;
}
```

We access the pseudo class by writing the element first, then semicolon, then the pseudo class we want to use. In this example, we set the font size of all h1 elements tp 20 pixels when the mouse is places on them.

- All types of pseudo classes are:
<ul>
    <li>:focus</li>
    <li>:visited</li>
    <li>:disabled</li>
    <li>:active</li>
</ul>

- Specifity ranking: id > class > type
- Chanining: We can combine different selector, say type and class and affect a specific element in our HTML file.

```HTML
<h1 class="affected">SUP</h1>
<h1 class="not-affected">SUUUP</h1>
```

```CSS
h1.affected {
    font-size: 20px;
}
```

This code will only change the h1 with the affected class and not the other. It can easily be comprehended by thinking of it as set intersection in maths.

- We can also refer to the children of an element by mentioning about the children after the parent.

```HTML
<ol class="parent">
    <li></li>
    <li></li>
    <li></li>
</ol>
```

```CSS
.parent li {
    color: red;
}
```

This can be done with any kind of specifier(as far as I know).

- It is possible to add style to different specifiers at once.

```CSS
.parent, #child, h1{
    color: red;
}
```
