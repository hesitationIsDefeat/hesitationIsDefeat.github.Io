---
layout: post
title: My Web Development Notes 5
subtitle: 
categories: Fundamentals-Of-HTML
tags: [Web, Html, Css, Js]
---

Here are my notes from the Fullstack Engineering Course of [Codecademy](https://www.codecademy.com/):

- table element: Helps us visualize data in 2-D format.
- tr element: Adds a row to a table.
- td element: Add a data to tr element.
- th element: Adds a heading to a row or a column.
- scope attribute: Identifies if the heading is for the row or the column.

```HTML
<table>
    <tr>
        <th></th>
        <th scope="col">Math 221</th>
        <th scope="col">Math 222</th>
    </tr>
    <tr>
        <th scope="row">Grades</th>
        <td>79</td>
        <td>-</td>
    </tr>
</table>
```

- colspan attribute: Defines how many columns a table entry will hold.
- rowspan attribute: Similar to colspan.
- tbody element: To indicate the body of a table.
- thead element: To indicate the headings of a table. It is used only for column headings.
- tfoot element: To indicate the end of a table. Often used for calculating sums for the columns of the table.

```HTML
<table>
    <thead>
        <tr>
            <th></th>
            <th scope="col">Math 221</th>
            <th scope="col">Math 222</th>
        </tr>
    </thead>
    <tbody>
    <tr>
        <th scope="row">Grades</th>
        <td>79</td>
        <td>-</td>
    </tr>
    </tbody>
    <tfoot>
        <th scope="row">Total</th>
        <td>>= 79</td>
    </tfoot>
</table>
```

