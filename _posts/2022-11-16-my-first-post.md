---
layout: post
title: Creating a post
subtitle: How did I manage to create my first post using VSCode
categories: Markdown
tags: [Markdown, journaling, blog, VSCode, Frontend]
---

# LETS BEGIN

**Disclamer:** I'm creating this post to test my learnings. The material I'll be talking about are coming from [Tech Expert Academy's site](https://tea-berlin.github.io/markdown/2022/02/12/document-your-learnings.html#h-create-a-post). Go check it out!

## HEADINGS

Usage of hashtag determines the level of my headings, which is quite important to divide the content into subgroups and divide them into subgroups as well and then ...

## CODE PARTS

Here is some Java code:

```Java

System.out.println("I'm some java code")

```

And here is some more Java code because Java rocks:

```Java

System.out.println("He's absolutely right")

```

Here is some Python code I wrote when I was bored:

```Python

import turtle
import math

def spirals(times, colored=True):
    length = 5
    angle = 3
    turtle.speed(10000)
    colors = ["Red", "Green", "Blue", "Purple", "Yellow", "Orange"]

    for one_round in range(times):
        for i in range(6):
            turtle.forward(length)
            turtle.right(60)
            if colored:
                turtle.pencolor(colors[i % 6])
        excess = (length * math.sin(math.radians(angle))) / math.sin(math.radians(120))
        length = (length * math.sin(math.radians(60 - angle))) / math.sin(math.radians(120)) + excess
        turtle.left(angle)
        turtle.back(excess)
    turtle.done()

spirals(130)

```

Here is some code w/o specifying the language:

```

x -> 3

```

## `

To `highlight` a text, we put it in between backticks.

## ITALIC & BOLD 

To make a text *italic*, we use a single star before and after the text. We use 2 for **bold** and 3 for ***italic and bold***.

## >

> Usage of a single greater before text segment highlight it.

## Links

Usage of brackets before and after a [text](https://open.spotify.com/user/onattanriover?si=c6329642c5f34864) turns it into a clickable. After the second bracket, we use parentheses to link it to **THE GREATEST SITE EVER**. Well, technically you can link it to any url you want.

## IMAGES

Images are very similar to links yet we have to put an exclamation mark before them.

![hesitation is defeat](https://i.insider.com/5c951ced16c958189c5c3b4c?width=700)

## BULLET POINTS

- We use the minus sign to make bullet points
    - and can create more levels through indentation
        - and she's buuuuying a
            - stairway to heeeaven

## NUMBERED LISTS

1. Point 1.0.0
    1.Point 1.1.0
        1. Point 1.1.1
    2. Point 1.2.0

## PUSHING TO GITHUB

I'm currently using VSCode to create and edit my posts. After I'm done I have to push it to Github, meaning I have to publish it. Here are the steps that I follow:

- Open a terminal
- Type
```
git status

git add .

git commit -m "this message describes the changes I've done"

git push origin main
```
- Enjoy myself

# CLOSURE

I'm starting a new journey of learning frontend and I'm ***BEYOND EXCITED*** as everyone on LinkedIn are. This is my first post, a marker for me to remember this very day in the future. I plan on posting regularly to see my progress. We'll see how it goes. Adios!