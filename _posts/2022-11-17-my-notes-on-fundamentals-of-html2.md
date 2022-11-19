---
layout: post
title: My Web Development Notes 4
subtitle: 
categories: Fundamentals-Of-HTML
tags: [Web, Html]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

To tell the browser what kind of document we'll be presenting, we put:

```HTML
<!DOCTYPE html>
```

This refers to the latest version of HTML.

Then, we write our code in the html element to prevent any kinds of confussions.

```HTML
<!DOCTYPE html>
<html>

</html>
```

head element: It is located above the body element and contains information about the page and isn't displayed on the page.

title element: It is placed in the head element and contains the title of the page.

a (anchor) element: Used for creating links.

href attribute: Used inside of an a element to link it to a certain url.

target attribute: Used inside of an a element. Setting it to _blank transfers the user to a new tab when the link is clicked.

Relative Path: A link to a file that is on the same folder as we

Absolute Path: The full link to a file

To turn an image into a link, we wrap it with an a (achor) element as follows:

```HTML
<!DOCTYPE html>
<html>
    <body>
        <a href="some url">
            <img src="some more url"/>
        </a>
    </body>
</html>
```

We can and probably should create internal links in the page to help the user directly reach the part of page. We can obtain this by crating a list of internal links as follows:

```HTML
<!DOCTYPE html>
<html>
    <body>
        <ul>
            <li><a href=#top>TOP</a></li>
            <li><a href=#mid>MID</a></li>
            <li><a href=#bottom>BOTTOM</a></li>
        <ul>
        <p id = top>Some top text</p>
        <p id = top>Some mid text</p>
        <p id = top>Some bottom text</p>
    </body>
</html>
```

Right now, I'll try to accomplish the same output with using Markdown and HTML. I'll try to understand if HTML code works on this page:

Using Markdown: **this is bold**
Using HTML: <strong>I hope this is bold as well</strong>

Whitespaces between HTML code are ignored by the browser.

Commenting: Using !-- and -- will allow you to comment inside af an HTML code, like // for Java and # for Python.

```HTML
    <!-- This is completely ignored -->
```

Mozilla Developer Network: It is claimed to the "go to site" when you need to look up anything on web development. The link is <a href="https://developer.mozilla.org/en-US/">here</a>.

A well written page on <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML">debugging</a>.

