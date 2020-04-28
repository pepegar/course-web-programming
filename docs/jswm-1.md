---
title: Programming Javascript for Web and Mobile
author: Pepe García
email: jgarciah@faculty.ie.edu
date: 2020-04-20
lang: en
---

Programming Javascript for Web and Mobile
=========================================


Grading system
==============

  Criteria              Score %
  --------------------- ---------
  Final Exam            20 %
  Individual Work       50 %
  Workgroups            20 %
  Class Participation   10 %

Code editors
============

So far we\'ve only used spyder for code editing, but it only works on
python.

 

Now we\'ll need other code editor:

Install VScode
==============

Install Visual Studio code from https://code.visualstudio.com/

 

(You may already have it from when you installed anaconda)

HTML tables
===========

Tables are created with the \<table\> element

    <table>
    </table>

HTML tables
===========

Content in HTML tables is added by creating rows and cells.

 

Rows are created with the \<tr\> element:

``` {.gams}
<table>
  <tr></tr>
  <tr></tr>
  <tr></tr>
</table>
```

This table will have three rows

HTML tables
===========

Finally, cells in tables are created with the \<td\> element

``` {.gams}
<table>
  <tr>
    <td>row 1, cell 1</td>
    <td>row 1, cell 2</td>
  </tr>
  <tr>
    <td>row 2, cell 1</td>
    <td>row 2, cell 2</td>
  </tr>
</table> 
```

Practice
========

Let\'s do exercise 1 from:\
\
https://github.com/mcsbt-web-programming-2020/session-1

CSS
===

\- What is CSS\
- how to add CSS to a webpage\
- cascading, precendence

CSS
===

CSS is a language to give style to webpages.

CSS
===

``` {.css}
p {
  color: 000;
  blackground: orange;
  padding: 15px;
}
```

Adding CSS to a webpage
=======================

There are several ways to add css to a webpage:

\- using the **style=\"\"** attribute

\- using the **\<style\>** html tag

\- loading the CSS from an external resource

Adding CSS to a webpage
=======================

one can use the **style** attribute to add style to an HTML element
directly

``` {.xml}
<p style="border:2px;">
this paragraph will have a two pixels border
</p>
```

Practice
========

Let\'s do exercise2 from\
\
https://github.com/mcsbt-web-programming-2020/session-1

Homework
========

Do exercise3 of\
\
https://github.com/mcsbt-web-programming-2020/session-1

Resources
=========

Free course to learn HTML: https://www.codecademy.com/courses/learn-html

Mozilla development network docs:

https://developer.mozilla.org/en-US/docs/Web/HTML

CSS Basic Properties:
http://web.simmons.edu/\~grabiner/comm244/weekthree/css-basic-properties.html
