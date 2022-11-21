---
layout: post
title: My Web Development Notes 9
subtitle: 
categories: Fundamentals-Of-CSS
tags: [Web, Html, Css]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- The Box Model: Every element is consisted of a content, a padding around the content, a border around the padding and a margin around, you gussed it right, the border. Since every part that I've mentioned is in a rectangular form (at least at default), every element can be seen as a collection of nested rectangles.

- content:
    - width
    - length
    - min-width
    - max-width
    - min-height
    - max-height

- border: <strong>medium none color (of the content)</strong> is the default value
    - width (thin, medium, thick)
    - style (none, dotted, solid)
    - color
    - border-radius: Gives a little curvature to the border.
    
    To make a complte circle, we can equalize the height and the weight and then set the border-radius value to 50%.

- padding:
    - padding-top
    - padding-right
    - padding-bottom
    - padding-left

    - It is possible to use shortcuts for this:
        - padding: a b c d; (defines all separately)
        - padding: a b c; (left and right are set to b)
        - padding: a b; (top and bottom are set to to a, left and right are set to b)

- margin: Controls are very similar to padding.
    - To center an element, we set the margin to "0 auto". 0 is for the vertical margins, and auto is for the horizontal. Be careful to assing a width value to the element in order to use this.
    - Horizontal distance b/w two elements is the sum of the horizontal margins while vertical distance is the max of the vertical margins.

- overflow: When a child element expands beyond the area of the parent element.
    - hidden: Hides the overflown content.
    - scroll: A scrollbar can be used to navigate.
    - visible: The overflown part will still be visible outside of the parent.

- visiblity:
    - hidden: hides the content of the element but the space reserved for it is still visible. "display: none;" can be used to hide the space for the element as well.
    - visible
    - collapse

- box-sizing property:
    - content-box: Default.
    - border-box: The height and the width of an element stays fixed.

