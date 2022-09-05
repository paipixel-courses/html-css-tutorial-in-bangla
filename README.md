# Learn HTML and CSS in 30 Days

|                             **Day**                             |                                                  **Topics**                                                   |
| :-------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|          [01](#h1-aligncenter-day-01-introduction-h1)           |                            [Introduction](#h1-aligncenter-day-01-introduction-h1)                             |
|                [02](./day-02-html-tags/DAY02.md)                |                                   [HTML Tags](./day-02-html-tags/DAY02.md)                                    |
| [03](./day-03-html-entities-links-images-audio-videos/DAY03.md) | [HTML Entities, Hyperlinks, Images, Audio, Videos](./day-03-html-entities-links-images-audio-videos/DAY03.md) |
|         [04](./day-04-list-tables-containers/DAY04.md)          |                     [List, Tables, Containers](./day-04-list-tables-containers/DAY04.md)                      |
|                               05                                |                                                                                                               |
|                               06                                |                                                                                                               |
|                               07                                |                                                                                                               |
|                               08                                |                                                                                                               |
|                               09                                |                                                                                                               |
|                               10                                |                                                                                                               |
|                               11                                |                                                                                                               |
|                               12                                |                                                                                                               |
|                               13                                |                                                                                                               |
|                               14                                |                                                                                                               |
|                               15                                |                                                                                                               |
|                               16                                |                                                                                                               |
|                               17                                |                                                                                                               |
|                               18                                |                                                                                                               |
|                               19                                |                                                                                                               |
|                               20                                |                                                                                                               |
|                               21                                |                                                                                                               |
|                               22                                |                                                                                                               |
|                               23                                |                                                                                                               |
|                               24                                |                                                                                                               |
|                               25                                |                                                                                                               |
|                               26                                |                                                                                                               |
|                               27                                |                                                                                                               |
|                               28                                |                                                                                                               |
|                               29                                |                                                                                                               |
|                               30                                |                                                                                                               |

# <h1 align="center"> Day-01: Introduction </h1>

- [What is HTML?](#what-is-html)
- [HTML Basics](#html-basics)
- [How Web Works?](#how-web-works)

## What is HTML?

---

The full meaning of HTML is **_Hyper Text Transfer Protocol_**. HTML is a Markup language.  
HTML is used to buld the **_STRUCTURE_** of the web pages.

## HTML Basics

---

- **`<DOCTYPE html>`** is used to **tell** the browser, this is an HTML5 document.
- **`<html>`** is the **container** of all HTML elements. This tag is used to **indicate** the beginning and end of all HTML elements in an HTML Document.

- **`<head>`** element is used to give **browser and search engine** informations about the page.
- **`<title>`** element specifies a title for the HTML page (which is shown in the browser's title bar and in the page's tab).
- **`<body>`** element is the container for all the visible contents such as headings, paragraphs, images, hyperlinks, tables, lists, etc in the webpage.
- The **`<em>`** element is used to define emphasized text. By default, emphasized text is
  displayed in _italic_.
- The **`<strong>`** element is used to represent important content. Browsers, by default, render strong content in **bold**.
- The **`<i>`** and **`<b>`** elements are considered deprecated because HTML should not be used for styling. That’s the role of CSS.
- Headings are represented using **`<h1>`**, **`<h2>`**, **`<h3>`**, **`<h4>`**, **`<h5>`**, **`<h6>`**. Every web page should have one and only one **`<h1>`** element. Headings should have a natural hierarchy and should not be skipped.
- Entities are used to display special characters such as angle brackets, copyright symbol, etc. The most important entities are: **`&nbsp;`** (non-breaking space), **`&lt;`** (less than sign), **`&gt;`** (greater than sign) and **`&copy;`** (copyright symbol).
- The **`<div>`** and **`<span>`** elements are generic containers used for styling purposes. Divs are block-level elements, spans are inline elements. A block-level element starts on a new line and takes up the entire available horizontal space.
- Semantic elements help us write markup that is more meaningful and descriptive to search engines, screen readers and other software. So, use **`<div>`** and **`<span>`** elements when no other semantic element is appropriate.
- The semantic elements in HTML5 are: **`<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>` and `<mark>.`**

  **An Example of Basic HTML Boilerplate is**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="keywords" content="Traveller Abdul Alim, Abdul Alim, Travel />
    <meta
      name="description"
      content="Alim is an passionate traveler who travels around the world and loves to make adventures"
    />
    <title>HTML Introduction</title>
  </head>
  <body></body>
</html>
```

## How Web Works?

---

Hey, rather wasting some time, I'm gonna provide you some useful resources to learn how the web works!
Here we go:

1. An amazing Video [Explanation](https://youtu.be/zN8YNNHcaZc) on freeCodeCamp.
2. Another Amazing [Explanation](https://github.com/vasanthk/how-web-works) by Vasa.
3. Video [Explanation](https://www.youtube.com/watch?v=hJHvdBlSxug) on Academind.
4. An [Explanation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) on Mozilla.

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

<h1 align="center"> Day-02: Commonly Used HTML Tags & Their Usage </h1>

- [&lt;em&gt;](#em)
- [&lt;i&gt; vs &lt;em&gt;](#i-vs-em)
- [&lt;strong&gt;](#strong)
- [&lt;b&gt; vs &lt;strong&gt;](#b-vs-strong)

## em

---

The **`<em>`** element is used to define emphasized text. By default, emphasized text is displayed in _italic_. However, it should not be used to apply italic styling; use the CSS `font-style` property for that purpose. Use the `<cite>` element to mark the title of a work (book, play, song, etc.). Use the `<i>` element to mark text that is in an alternate tone or mood, which covers many common situations for italics such as scientific names or words in other languages. Use the `<strong>` element to mark text that has greater importance than surrounding text.<br>
Visit [HERE](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em) for learning more about this element.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="keywords"
      content="TravellerAlim, Alim, Travel, AlimTheTraveller"
    />
    <meta
      name="description"
      content="Alim is an passionate traveler who travels around the world and loves to make adventures"
    />
    <title>TravellerAlim</title>
  </head>
  <body>
    <article>
      Cox’s Bazar is a town on the southeast coast of <em>Bangladesh</em>.
    </article>
  </body>
</html>
```

**Output:**
Cox’s Bazar is a town on the southeast coast of _Bangladesh_.

## i vs em

---

New developers are often confused at seeing multiple elements that produce similar results. `<em>` and `<i>` are a common example, since they both italicize text. What's the difference? Which should you use?

By default, the visual result is the same. However, the semantic meaning is different. The `<em>` element represents stress emphasis of its contents, while the `<i>` element represents text that is set off from the normal prose, such a foreign word, fictional character thoughts, or when the text refers to the definition of a word instead of representing its semantic meaning. (The title of a work, such as the name of a book or movie, should use `<cite>`.)

This means the right one to use depends on the situation. Neither is for purely decorative purposes, that's what CSS styling is for.

An example for `<em>` could be: "Just _do_ it already!", or: "We _had_ to do something about it". A person or software reading the text would pronounce the words in italics with an emphasis, using verbal stress.

An example for `<i>` could be: "The _Queen Mary_ sailed last night". Here, there is no added emphasis or importance on the word "Queen Mary". It is merely indicated that the object in question is not a queen named Mary, but a ship named _Queen Mary_. Another example for `<i>` could be: "The word _the_ is an article".

**Example:**

```html
<p>
  In HTML 5, what was previously called
  <em>block-level</em> content is now called <em>flow</em> content.
</p>
```

**Result/Output:**
In HTML 5, what was previously called _block-level_ content is now called _flow_ content.

Thanks [Mozilla Developer Network-MDN](https://developer.mozilla.org/en-US/docs/MDN/About) for [this awesome documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em).

## strong

---

The `<strong>` element indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.

The `<strong>` element is for content that is of "strong importance," including things of great seriousness or urgency (such as warnings). This could be a sentence that is of great importance to the whole page, or you could merely try to point out that some words are of greater importance compared to nearby content.

Typically this element is rendered by default using a bold font weight. However, it should not be used to apply bold styling; use the CSS `font-weight` property for that purpose. Use the `<b>` element to draw attention to certain text without indicating a higher level of importance. Use the `<em>` element to mark text that has stress emphasis.

Another accepted use for `<strong>` is to denote the labels of paragraphs which represent notes or warnings within the text of a page.

## b vs strong

---

It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. `<b>` and `<strong>` are perhaps one of the most common sources of confusion, causing developers to ask "Should I use `<b>` or `<strong>`? Don't they both do the same thing?"

Not exactly. The `<strong>` element is for content that is of greater importance, while the `<b>` element is used to draw attention to text without indicating that it's more important.

It may help to realize that both are valid and semantic elements in HTML5 and that it's a coincidence that they both have the same default styling (boldface) in most browsers (although some older browsers actually underline `<strong>`).

Each element is meant to be used in certain types of scenarios, and if you want to bold text for decoration, you should instead actually use the CSS `font-weight` property.

The intended meaning or purpose of the enclosed text should be what determines which element you use. Communicating meaning is what semantics are all about.

### em vs strong

---

While `<em>` is used to change the meaning of a sentence as spoken emphasis does ("I _love carrots_" vs. "I love _carrots_"), `<strong>` is used to give portions of a sentence added importance (e.g., "**Warning**! This is **very dangerous**.") Both `<strong>` and `<em>` can be nested to increase the relative degree of importance or stress emphasis, respectively.

### Example:

**Hope** is a good thing, maybe the best of things and no good thing ever dies.

[Visit here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) to learn more.

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)
