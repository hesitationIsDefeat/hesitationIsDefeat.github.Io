---
layout: post
title: My Web Development Notes 15
subtitle: 
categories: Making-a-Website-Responsive
tags: [Css]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- Responsive Units:
    - em: Default font size of the web browser.
    - rem: Font size of the root element.
    - min-width, max-width, min-height, max-height.
    - Setting a value to the height or witdh and setting the other one to auto will ensure that the one with the auto value will enlarge depending on the other one.

- Meta:
    ```CSS
    <!DOCTYPE html>
    <head> 
        <meta name="viewport", content="width=device-width, initial-scale=1">
    </head>
    ```
    - name="viewport": Used to display the page with the width of the screen.
    - width=device-width: Used to set the width of the viewport same as the width of the screen.
    - initial-scale=1: Sets the initial zoom level.

- Media Queries:
    ```CSS
    @media only screen and (min-width: 300px) and (max-width: 600px) {
    p {
    font-size: 15px;
    }
    }
    ```
    - This query changes the font size of the paragraphs to 15 pixels when the width is in the given range.

    ```CSS
    @media only screen and (min-resolution: 150dpi) {
    
    }
    ```
    - This query is applied when the resolution of the used screen has at least 150 dpi.
    - dpi: Dots per inch.
    - dpc: Dots per centimeter.

    ```CSS
    @media only screen and (condition1), (condition2) {
    
    }
    ```
    - This query requires any one of the conditions to be true in order to be executed. Is like "or" in logic.

    - text-shadow: Adds a shadow to the text, like box-shadow would do to a box.
    




