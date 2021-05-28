# Lesson 5: CSS

## What is CSS?
    - CSS stands for Cascading Style Sheets
        * CSS allows you to control exactly how you want to present your HTML elements
        * It is a rule-based language. Meaning you define rules for specific elements or set of elements to present in your webpage.

## How to add CSS:
    CSS is insterted in 3 fashions:
        * External CSS
        * Internal CSS
        * Inline CSS

        -External CSS
            * Can change the presenetation of an entire website by utilizing a separate file.
            * Each HTML page must have a reference inserted. This is defined with <link>.
                Example:<link rel="cssstylesheet" href="style.css">

            * Can be written in any text editor. ### Must be saved with .css extension.
            * Shouldn't contain HTML tags.

        -Internal CSS
            * May be used if you'd only like to style one singular HTML page.
            * Defined with the <style> element. (Placed in side head section.)
                Example: <head>
                         <style>
                         h1 {color: wierd'
                         }
                         </style>
                         </head>

        -Inline CSS
            * Used to apply styling for singular elements within an HTML doc.
            * Also defined by using 'style'.
                Example: <p style="text-align:center;">

    Cascading Order:
        - So what if there is more than one specified 'style' for HTML elements? It will 'cascade' into a new style sheet following the rules below. Top to bottom it will generate:

            *Inline style
            *External and internal style sheets 
            *Browser default

[Back to Read Me](README.md) |
[Reading 1](markdown.md) |
[Reading 2](coderscomputer.md) |
[Reading 3](revisionandthecloud.md) |
[Reading 4](html.md)