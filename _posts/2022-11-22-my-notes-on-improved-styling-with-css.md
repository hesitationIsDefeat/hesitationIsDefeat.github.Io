---
layout: post
title: My Web Development Notes 11
subtitle: 
categories: Improved-Styling-With-CSS
tags: [Css]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- color:
    - Can be set with names.
    - Can be set with hexadecimal (e.g. #FFFFFF is white).
    - Can be set with rgb(0-255, 0-255, 0-255).
    - Can be set with hsl(0-360, %, %).
    - Can be set with hsla(hsl, 0-1) or rgba(rgb, 0-1).

- Typography:
    - font-family:
        - When the name of a font consists more than one word, it is recommended to put it in quotation marks.
        - Fallback Fonts: Declaring couple of font names would give the browser other options if one font isn't available.
        ```CSS
        h1 {
            font-family: option1, option2, option3;
        }
        ```
        - Serif and Sans-Serif: Serif fonts include more details on the letters whereas sans-serif fonts don't. Serif can also be passes as a fallback font.

    - font-weight: Can be set with int values or with reserved keywords.
        - bold: 700.
        - normal: 400.
        - lighter: One font weight lighter than the parent.
        - bolder: One font weight bolder than the parent.

    - font-style: Normal or italic.

    - text-transform: Uppercase or lowercase.

    - Text Layout:
        - letter-spacing: Sets the spaces b/w each letter.
        - word-spacing: Sets the spaces b/w each word.
        - line-height: ets the vertical spaces b/w each line.
        - text-aling: right, left, center, justify
        - font-face: It is a way to download fonts from the internet and use them in the css files.
        ```CSS
        @font-face {
            font-family: 'My font name';
            src: url("some url") format('woff2'), url("some more url") format('woff');
        }

        ```
        



