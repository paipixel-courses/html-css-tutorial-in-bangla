<h1 align="center"> Day-02: Commonly Used HTML Tags & Their Usage </h1>

  - [&lt;em&gt;](#ltemgt)
  - [HTML Basics](#html-basics)
  - [How Web Works?](#how-web-works)
  
  

### &lt;em&gt;
---
The **`<em>`** element is used to define emphasized text. By default, emphasized text is
displayed in *italic*.
**Example:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="TravellerAlim, Alim, Travel, AlimTheTraveller">
    <meta name="description" content="Alim is an passionate traveler who travels around the world and loves to make adventures">
    <title>TravellerAlim</title>
</head>
<body>
    <article>
        Cox’s Bazar is a town on the southeast coast of Bangladesh. It’s known for its very long, 
        sandy beachfront, stretching from Sea Beach in the north to Kolatoli Beach in the south. 
        Aggameda Khyang monastery is home to bronze statues and centuries-old Buddhist manuscripts. 
        South of town, the tropical rainforest of Himchari National Park has waterfalls and many 
        birds. North, sea turtles breed on nearby Sonadia Island.
    </article>
</body>
</html>
```

### HTML Basics
---
- **`<DOCTYPE html>`** is used to **tell** the browser, this is an HTML5 document.
- **`<html>`** is the **container** of all HTML elements. This tag is used to **indicate** the beginning and end of all HTML elements in an HTML Document.

- **`<head>`** element is used to give **browser and search engine** informations about the page.
- **`<title>`** element specifies a title for the HTML page (which is shown in the browser's title bar and in the page's tab).
- **`<body>`** element is the container for all the visible contents such as headings, paragraphs, images, hyperlinks, tables, lists, etc in the webpage.
- The **`<em>`** element is used to define emphasized text. By default, emphasized text is
displayed in *italic*.
- The **`<strong>`** element is used to represent important content. Browsers, by default, render strong content in **bold**.
- The **`<i>`** and **`<b>`** elements are considered deprecated because HTML should not be used for styling. That’s the role of CSS.
- Headings are represented using **`<h1>`**, **`<h2>`**, **`<h3>`**, **`<h4>`**, **`<h5>`**, **`<h6>`**. Every web page should have one and only one **`<h1>`** element. Headings should have a natural hierarchy and should not be skipped.
- Entities are used to display special characters such as angle brackets, copyright symbol, etc. The most important entities are: **`&nbsp;`** (non-breaking space), **`&lt;`** (less than sign), **`&gt;`** (greater than sign) and **`&copy;`** (copyright symbol).
- The **`<div>`** and **`<span>`** elements are generic containers used for styling purposes. Divs are block-level elements, spans are inline elements. A block-level element starts on a new line and takes up the entire available horizontal space.
- Semantic elements help us write markup that is more meaningful and descriptive to search engines, screen readers and other software. So, use **<div>** and **<span>** elements when no other semantic element is appropriate.
- The semantic elements in HTML5 are: **`<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>` and `<mark>.`**
<br>



  
  **An Example of Basic HTML Boilerplate is**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our First Webpage</title>
</head>
<body>
    
</body>
</html>
```

### How Web Works?
---
Hey, rather wasting some time, I'm gonna provide you some useful resources to learn how the web works! 
Here we go:
1. An amazing Video [Explanation](https://youtu.be/zN8YNNHcaZc) on freeCodeCamp.
2. Another Amazing [Explanation](https://github.com/vasanthk/how-web-works) by Vasa.
3. Video [Explanation](https://www.youtube.com/watch?v=hJHvdBlSxug) on Academind.
4. An [Explanation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) on Mozilla.

