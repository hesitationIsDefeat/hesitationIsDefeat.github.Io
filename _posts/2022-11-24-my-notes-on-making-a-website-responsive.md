---
layout: post
title: My Web Development Notes 13
subtitle: 
categories: Making-a-Website-Responsive
tags: [Css]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- Grid Anatomy:
    <ol>
      <li>Column: Vertical blocks that divide the page into equal pieces.</li>
      <li>Gutter: The space b/w the columns.</li>
      <li>Margin: The spaces b/w the most right and left elements and the actual page's sides.</li>
      <li>Row: Horizontal versions of a column.</li>
    </ol>

- Passive/Micro Whitespace: Used for achieving a better look.
- Active/Macro Whitespace: Used for guiding the user.

- Flexbox:

    - Flex Container: Contains flex items.
        - display must be set to flex or inline-flex.
        - flex: Block level, no other items will be seen on the same horizontal line with it.
        - inline-flex: Not block level.
    - justify-content:
        - flex-start: Elements start aligning from the left.
        - flex-end: Elements start aligning from the right.
        - center: Elements start aligning from the center.
        - space-around: Doubles the space b/w the elements.
        - space-between: Doubles the space b/w the elements w/o the spaces at the start and the end.
    - align-items:
        - flex-start: Elements start aligning from the top of the parent.
        - flex-end: Elements start aligning from the bottom of the parent.
        - center: Elements start aligning from the center of the parent.
        - baseline: The bottom of all elements will be aligned.
        - flex-wrap:
            - wrap: Flex items that don't fit will move to the next line.
            - wrap-reverse: No idea currently :(
            - nowrap: Default.
        - align-content:
            - flex-start: Rows of flex elements start aligning from the top of the parent.
            - flex-end: Rows of flex elements start aligning from the bottom of the parent.
            - center: Rows of flex elements start aligning from the center of the parent.
            - space-around: Rows of flex elements align from the top with equal spaces at the top, between elements and at the bottom.
            - space-between: Rows of flex elements align from the top with equal spaces in between.
            - flex-direction:
                - row: Default.
                - row-reverse: Flex items are now aligned right to left
                - column: Flex items are now aligned top to bottom.
                - column-reverse: Flex items are now aligned bottom to top.
            - flex-flow: Used for declaring flex-direction and flex-wrap in one line.

    - Flex Item: Flexes all over the place.
        - flex-grow: Takes an integer value (I suppose) and determines the ratio b/w the growth quantitites of flex elements in the same flex container.
        - flex-shrink: Same for shrinking.
        - flex-basis: Determines the dimentions of an element if there is sufficient amount of space.
        - flex: Allows setting flex-grow, flex-shrink and flex-basis in one line.
        





