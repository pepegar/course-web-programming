---
title: Programming Javascript for Web and Mobile
subtitle: Session 1
author: Pepe García <jgarciah@faculty.ie.edu>
email: jgarciah@faculty.ie.edu
---



# Grading system

| Criteria            | Score % |
|:--------------------|:--------|
| Individual Work     | 50 %    |
| Workgroups          | 35 %    |
| Class Participation | 15 %    |

# Syllabus


# SESSION 1 (FACE TO FACE)

## Course presentation.

In this session we will introduce the course, the syllabus, materials
we're going to use, and grading system.

## Frontend development.

During this course we will learn how to create dynamic web
applications using HTML, CSS, and Javascript. We will also learn some
of the tools of the modern web developer, such as Yarn and Jest.

# SESSION 2 (NON-CLASS LEARNING)

## CSS

In this session we will learn about CSS.  Students will go over a
Codecademy session.  They will also be able to test their CSS
abilities with https://flukeout.github.io/


# SESSIONS 3 & 4 (FACE TO FACE)

Javascript for the web

# SESSION 5 (NON-CLASS LEARNING)

## Communication between frontend and backend

In order to make our frontend applications communicate with the
backend we will make requests from Javascript.  In this session we
will learn about using the fetch() function in JS, promises, and
sending and receiving JSON from the server.

The professor will record a video for this session for students to
follow along.

# SESSION 6 (FACE TO FACE)

## Communication between frontend and backend

In this second session about the communication between frontend and
backend we will go over what we learnt last session and also do a
small exercise in class.

# SESSION 7 (NON-CLASS LEARNING)

## Individual assignment 1

In this session students will do an individual exercise on their own.
There will be an open forum in campus for them to ask questions if
they have any.

# SESSION 8 (FACE TO FACE)

## Box model

In this session we will learn about the box model in CSS.  We will
learn how to position things in a web page and how this box model
makes elements interact with others.

# SESSION 9 (NON-CLASS LEARNING)

## Box model

In this session we will learn about the box model in CSS.  We will
learn how to position things in a web page and how this box model
makes elements interact with others.

# SESSION 10 (FACE TO FACE)

## Frontend UI frameworks

In this session we will learn about Bootstrap one of the many frontend
frameworks for creating interfaces.  Using these kinds of frameworks
can make prototyping our websties much faster, and will also help us
grow the UI architecture of our site in an easier way.

# SESSION 11 (NON-CLASS LEARNING)

## Group assignment 1

In this session students will do an individual exercise on their own.
There will be an open forum in campus for them to ask questions if
they have any.

# SESSION 12 (FACE TO FACE)

## QA session

In this session we will do a whirlwind tour over what we have learned
in the course and we will have time to answer questions students may
have


# Github Classroom

Please join the GH classroom,

https://classroom.github.com/a/8iCf1YR4


# Code editors

So far we've used Spyder for code editing, but for this course we'll
change to a better editor.


# Install VScode

Install Visual Studio code from https://code.visualstudio.com/

(You may already have it from when you installed anaconda)


# CSS

- What is CSS
- how to add CSS to a webpage
- cascading, precendence


# CSS

CSS is a language to give style to webpages.


# CSS

``` {.css}
p {
  color: 000;
  blackground: orange;
  padding: 15px;
}
```

**`p`** is the selector, and refers to which tags do these rules
apply.  In this case, we're applying it to **`<p>`** tags.

`color: 000;`, `blackground: orange;`, and `padding: 15px;` are CSS properties.


# Adding CSS to a webpage

There are several ways to add css to a webpage:

- `*` using the **style=""** attribute
- `*` using the **`<style>`** html tag
- `*` loading the CSS from an external resource


# Adding CSS to a webpage

one can use the **style** attribute to add style to an HTML element
directly

``` {.html}
<p style="border:2px;">
this paragraph will have a two pixels border
</p>
```


# Adding CSS to a webpage

It's also possible to embed a piece of CSS inside an HTML `<style>` tag:

```html
<style>
p {
  color: red;
}
</style>
```


# Adding CSS to a webpage

Finally, the most common way of adding CSS to a webpage, is using the
`<link>` tag.  We'll be able to create standalone CSS files and link
them to our HTML with it.


```html
<link rel="stylesheet" href="./styles/file.css">
```

We can pass any URL or path to the `href` attribute.

# Practice

Let's do exercise1 from

https://github.com/mcsbtp-web-programming-2021/session-1


# Homework

Do exercise2 of

https://github.com/mcsbtp-web-programming-2021/session-1


# Resources

Mozilla development network docs:
<https://developer.mozilla.org/en-US/docs/Web/CSS>

CSS Basic Properties:
<http://web.simmons.edu/~grabiner/comm244/weekthree/css-basic-properties.html>
