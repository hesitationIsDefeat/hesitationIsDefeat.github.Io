---
layout: post
title: My Web Development Notes 14
subtitle: 
categories: Making-a-Website-Responsive
tags: [Css]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- grid:
    - grid container:
        - display: grid or inline-grid.
        - grid-template-columns: 
            - Creates columns as many as the arguments it was given.
            - Every argument is defines the width of the columns, either as pixels or percentages.
        - grid-template-rows: Similar to columns.
        - grid-template: rows / columns.
        - fr (fractions): A unit used in grids.
        - repeat(a, b): Used for creating rows or columns. A is the number of times it executes and b is the value that is repeated.
        - minmax(a, b): Prevents a column or a row from passing the specified limits.
        - row-gap and column gap: Defines gaps b/w rows and columns.
        - gap: row-gap column-gap.
        - grid-template-areas: Used to name the grid elements to place them with actual elements. The name is later passed to the grid-area property.
        - justify-items: Horizontal, used for aligning grid-items in their cells:
            - start
            - end
            - center
            - stretch
        - justify-content: Horizontal, used for aligning all grid items inside fo the grid:
            - start
            - end
            - center
            - stretch
            - space-around:
            - space-between:
            - space-evenly:
        - align-items: Vertical, used for aligning grid-items in their cells:
            - start
            - end
            - center
            - stretch
        - align-content: Horizontal, used for aligning all grid items inside fo the grid:
            - start
            - end
            - center
            - stretch
            - space-around:
            - space-between
            - space-evenly
        - implicit grid: When the number of grid elements exceeds the the number of cells.
        - grid-auto-row and grid-auto-column: Defines the height or the width of the newly added element.
        - grid-auto-flow: Controls the behaviour of the grid container when a new element is added and there isn't an empty cell for it:
            - row: It is added to a new row (default).
            - column: It is added to a new column.
            - dense: Some kind of witchcraft.

    - grid item:
        - grid-row-start: Determines the row a grid item start.
        - grid-row-end: Determines the row a grid item ends (excluded).
        - grid-row: start / end.
        - grid-column-start: Similar.
        - grid-column-end: Similar.
        - grid-column: Similar.
        - span a: Can be used to specify how many rows or columns an element is goind to span. Used as a value for the end.
        - grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end.
        - justify-self and align-self: 
            - start
            - end
            - center
            - stretch




        



