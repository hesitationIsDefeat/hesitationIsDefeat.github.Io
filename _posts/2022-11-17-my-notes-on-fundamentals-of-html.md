---
layout: post
title: My Web Development Notes 3
subtitle: 
categories: Fundamentals-Of-HTML
tags: [Web, Html, Css, Js]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

"body" is used for containing multiple HTML elements.

```HTML
<body>
    <button> I'm a button </button>
    <h1> I'm some text </h1>
    <p> I'm much more text </p>
</body>
```

When an element is placed inside of another element, it becomes the child of that element and we say it is nested of the parent element.

The general name of this relation is called hierarchy and can be extented to any degree.

Headings: h1, h2, h3, h4, h5 and h6 are used for creating headings and are ordered from the largest to the smallest.

div element: short for divison and helps grouping the related HTML elements. Also helps us to apply a specific style only to the elements it contains.

```HTML
<body>
    <div>
        <button> I'm a button </button>
        <h2> I'm not a button </h2>
    </div>
    <h1> I may or may not be a button </h1>
</body>
```

id attribute: It is like giving an element a name to refer to it in other places.

p element: Used for creating paragraphs

span element: It is used for separating a part of a from the rest. I assume it will be used for applying a style format to that specified part and not to the whole.

```HTML
<body>
    <p>This is a paragraph with lots and lots and lots and ..... of words but
        <span id= "seperated part">this part is seperated and has an id attribute<span> but this last part doesn't.</p>
</body>
```

em tag: Creates an ithalic text.

strong tag: Creates a bold text.

```HTML
<body>
    <p><em>This part is ithalic</em> and <strong>this part is bold</strong>.</p>
</body>
```

br element: Adds a line break and doesn't require a closing tag.

ul element: A list with unordered elements.

ol element: A list with ordered elements.

li element: Used for creating list items.

img element: Requres a src attribute to render an image. Has it's own closing tag.

alt attribute: This is added to the src element and describes the image. It is usefull if the image rejects to load.

```HTML
<body>
    <img src="some url" alt="some description"/>
</body>
```

video element: Similar to the img element, it is used for videos.

width and height attributes: Customizes the size of the video.

controls attribute: Adds basic video controls.

The text between the tags is what will be displayed if the video cannot be loaded.

```HTML
<body>
    <video src="some url" width = 1920 length = 1080 controls>
        No Video For You Today Bud
    </video>
</body>
```




