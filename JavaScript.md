# JavaScript

## Tutorial

### Introduction

JavaScript is one of the 3 languages all web developers must learn:

1. HTML to define the **content** of web pages
2. CSS to specify the **layout** of web pages
3. JavaScript to program the **behavior** of web pages

Versions of JavaScript:

1. JavaScript was invented by Brendan EIch in 1995.
2. The Original JavaScript ES1 ES2 ES3 (1997-1999)
3. The First Main Revision ES5 (2009)
4. The Second Revision ES6 (2015)
5. All Yearly Additions (2016, 2017, 2018, 2019, 2020)

What JavaScript can do:

1. JS can change HTML content
2. JS can change HTML attribute values
3. JS can change HTML styles (CSS): `document.getElementById("demo").style.fontSize = "35px";`
4. JS can hide/show HTML elements: `document.getElementById("demo").style.display="none/block";`

JavaScript accepts both double and single quotes.

### Where to

Placing scripts at the bottom of the `<body>` element improves the display speed, because script interpretation slows down the display.

To use an external script, put the name of the script file in the src (source) attribute of a `<script>` tag: `<script src="myScript.js"></script>`

External scripts cannot contain `<script>` tags.

External JavaScript Advantages

1. It separates HTML and code
2. It makes HTML and JavaScript easier to read and maintain
3. Cached JavaScript files can speed up page loads

File Path Examples:

| Path | Description |
| ---- | ---- |
| `<img src="picture.jpg">` | The "picture.jpg" file is located in the same folder as the current page |
| `<img src="images/picture.jpg">` | The "picture.jpg" file is located in the images folder in the current folder |
| `<img src="/images/picture.jpg">` | The "picture.jpg" file is located in the images folder at the root of the current web |
| `<img src="../picture.jpg">` | The "picture.jpg" file is located in the folder one level up from the current folder |

### Output

In JavaScript, the `window` object is the global scope object. This means that variables, properties, and methods by default belong to the `window` object.

### Syntax

**Values:**

- fixed values (literals)
- variable values (variables)

**Expression:**

An expression is a combination of values, variables, and operators, which computes to a value. The computation is called an evaluation.

**Identifier:**

must begin with

1. A letter (A-Z or a-z)
2. A dollar sign ($) or
3. An underscore (_)

Subsequent characters may be letters, digits, underscores, or dollar signs.

All JavaScript identifiers are **case sensitive**.

Hyphens are not allowed in JavaScript. They are reserved for subtractions.

**Character set:**

JavaScript uses the Unicode character set.

Unicode covers (almost) all the characters, punctuations, and symbols in the world.

### Variables
