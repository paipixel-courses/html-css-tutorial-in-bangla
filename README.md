# Learn HTML and CSS in 30 Days

|                            **Day**                            |                                                  **Topics**                                                   |
| :-----------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                  [01](#day-01-introduction)                   |                                     [Introduction](#day-01-introduction)                                      |
|      [02](#day-02-commonly-used-html-tags--their-usage)       |                           [HTML Tags](#day-02-commonly-used-html-tags--their-usage)                           |
|  [03](#day-03-html-entities-hyperlinks-images-audio-videos)   |   [HTML Entities, Hyperlinks, Images, Audio, Videos](#day-03-html-entities-hyperlinks-images-audio-videos)    |
|                            [04]()                             |
|                              05                               |                                                                                                               |
|                              06                               |                                                                                                               |
|                              07                               |                                                                                                               |
|                              08                               |                                                                                                               |
|                              09                               |                                                                                                               |
|                              10                               |                                                                                                               |
|          [11](#day-11-css-position-z-index-overflow)          |                   [CSS Position, Z-index, Overflow](#day-11-css-position-z-index-overflow)                    |
|               [12](#day-12-float-display-align)               |                    [CSS Float, Display and Alignment](#day-12-css-float-display-alignment)                    |
|                   [13](#day-13-css-flexbox)                   |                                      [CSS Flexbox](#day-13-css-flexbox)                                       |
|                              14                               |                                                                                                               |
|                              15                               |                                                                                                               |
|                              16                               |                                                                                                               |
|                              17                               |                                                                                                               |
|                              18                               |                                                                                                               |
|     [19](#day-19-visualize-and-play-with-css-properties)      |           [Visualize and Play with CSS Properties](#day-19-visualize-and-play-with-css-properties)            |
|                    [20](#css-grid-layout)                     |                                      [CSS Grid Layout](#css-grid-layout)                                      |
| [21](#day-21-css-gradient-shadows-text-effects-and-web-fonts) | [CSS Gradients, Shadows, Text Effects and Web Fonts](#day-21-css-gradient-shadows-text-effects-and-web-fonts) |
|                              22                               |                                                                                                               |
|                              23                               |                                                                                                               |
|                              24                               |                                                                                                               |
|                              25                               |                                                                                                               |
|                              26                               |                                                                                                               |
|                              27                               |                                                                                                               |
|                              28                               |                                                                                                               |
|                              29                               |                                                                                                               |
|                              30                               |                                                                                                               |

# Day-01: Introduction

- [What is HTML?](#what-is-html)
- [HTML Basics](#html-basics)
- [How Web Works?](#how-web-works)

### What is HTML?

The full meaning of HTML is **_Hyper Text Transfer Protocol_**. HTML is a Markup language.  
HTML is used to buld the **_STRUCTURE_** of the web pages.

### HTML Basics

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
  <body></body>
</html>
```

### How Web Works?

Hey, rather wasting some time, I'm gonna provide you some useful resources to learn how the web works!
Here we go:

1. An amazing Video [Explanation](https://youtu.be/zN8YNNHcaZc) on freeCodeCamp.
2. Another Amazing [Explanation](https://github.com/vasanthk/how-web-works) by Vasa.
3. Video [Explanation](https://www.youtube.com/watch?v=hJHvdBlSxug) on Academind.
4. An [Explanation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) on Mozilla.

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-02: Commonly Used HTML Tags & Their Usage

- [&lt;em&gt;](#em)
- [&lt;i&gt; vs &lt;em&gt;](#i-vs-em)
- [&lt;strong&gt;](#strong)
- [&lt;b&gt; vs &lt;strong&gt;](#b-vs-strong)

### em

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

### i vs em

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

### strong

The `<strong>` element indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.

The `<strong>` element is for content that is of "strong importance," including things of great seriousness or urgency (such as warnings). This could be a sentence that is of great importance to the whole page, or you could merely try to point out that some words are of greater importance compared to nearby content.

Typically this element is rendered by default using a bold font weight. However, it should not be used to apply bold styling; use the CSS `font-weight` property for that purpose. Use the `<b>` element to draw attention to certain text without indicating a higher level of importance. Use the `<em>` element to mark text that has stress emphasis.

Another accepted use for `<strong>` is to denote the labels of paragraphs which represent notes or warnings within the text of a page.

### b vs strong

It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. `<b>` and `<strong>` are perhaps one of the most common sources of confusion, causing developers to ask "Should I use `<b>` or `<strong>`? Don't they both do the same thing?"

Not exactly. The `<strong>` element is for content that is of greater importance, while the `<b>` element is used to draw attention to text without indicating that it's more important.

It may help to realize that both are valid and semantic elements in HTML5 and that it's a coincidence that they both have the same default styling (boldface) in most browsers (although some older browsers actually underline `<strong>`).

Each element is meant to be used in certain types of scenarios, and if you want to bold text for decoration, you should instead actually use the CSS `font-weight` property.

The intended meaning or purpose of the enclosed text should be what determines which element you use. Communicating meaning is what semantics are all about.

### em vs strong

While `<em>` is used to change the meaning of a sentence as spoken emphasis does ("I _love carrots_" vs. "I love _carrots_"), `<strong>` is used to give portions of a sentence added importance (e.g., "**Warning**! This is **very dangerous**.") Both `<strong>` and `<em>` can be nested to increase the relative degree of importance or stress emphasis, respectively.

### Example:

**Hope** is a good thing, maybe the best of things and no good thing ever dies.

[Visit here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) to learn more.

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-03: HTML Entities, Hyperlinks, Images, Audio, Videos

- [HTML Entities](#html-entities)
- [Hyperlinks](#hyperlinks)

### HTML Entities

Some characters are reserved in HTML. If you use the less than (<) or greater than (>) signs in your text, the browser might mix them with tags.
Character entities are used to display reserved characters in HTML.
**_Here are the list of some HTML Entities:_**
| Entity | Description | Entity Name |
|:------:|:---------------------------------:|:-----------:|
| | non-breaking space | `&nbsp;`| |
| < | less than | `&lt;` |
| > | greater than | `&gt;` |
| & | ampersand | `&amp;` |
| " | double quotation mark | `&quot;` |
| ' | single quotation mark(apostrophe) | `&apos;` |
| £ | pound | `&pound;` |
| € | euro | `&euro;` |
| © | copyright | `&copy;` |
| ® | registered trademark | `&reg;` |

**Note:** Entities names are case-sensitive.
Here is the [HTML](table.html) and [CSS](table.css) code that generates all the entites listed above.

### Hyperlinks

### What is Hyperlinks?

Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address (URL).

### HTML Link Syntax

The HTML `<a>` tag defines a hyperlink. It has the following syntax:

```html
<a href="url">link text</a>
```

The most important attribute of the `<a>` element is the **_href_** attribute, which indicates the link's destination.

The **link text** is the part that will be visible to the reader. Clicking on the link text, will send the reader to the specified URL address.

#### Example:

```html
<a href="https://www.travelerabdulalim.com/">Visit My Travel Blog</a>
```

#### Output:

[Visit My Travel Blog](https://www.travelerabdulalim.com/)

### HTML Links - The target Attribute

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.
The **_target_** attribute specifies where to open the linked document.
The **target** attribute can have one of the following values:

- `_self` : Default. Opens the document in the same window/tab as it was clicked.
- `_blank` : Opens the document in a new window or tab.
- `_parent` : Opens the document in the parent frame.
- `_top` : Opens the document in the full body of the window.

View the [Source Code](hyperlinks.html) to see the application of these attributes.

### HTML Links - The title Attribute

The **title** contains additional information about the link, we can see the **title** text while hovering the link.

Click the [Source Code](hyperlinks.html) to view the application of **title** attribute.

### Absolute URL vs. Relative URL

**Absolute URL:**
Points to a location defined by its absolute location on the web, including protocol and domain name.For example, if an `index.html` page is uploaded to a directory called `projects` that sits inside the **root** of a web server, and the website's domain is `https://www.example.com`, the page would be available at `https://www.example.com/projects/index.html`

An absolute URL will always point to the same location, no matter where it's used.

**Relative URL:**
Points to a location that is _relative_ to the file you are linking from, more like what we looked at in the previous section. For example, if we wanted to link from our example file at `https://www.example.com/projects/index.html` to a PDF file in the same directory, the URL would just be the filename — `project-brief.pdf` — no extra information needed. If the PDF was available in a subdirectory inside `projects` called `pdfs`, the relative link would be `pdfs/project-brief.pdf`(the equivalent absolute URL would be `https://www.example.com/projects/pdfs/project-brief.pdf`)

View the [SOURCE CODE](/day-03-html-entities-links-images-audio-videos/hyperlinks.html) here.

#### A Real Example of Absolute and Relative URL

Assume we are creating a subsite whose files are in the folder https://paipixel.com/shop.

**1. Absolute URL**

```javascript
   Link to home page
   href="https://paipixel.com/shop/"

   Link to the product page
   href="https://paipixel.com/shop/t-shirts/t-shirt-life-is-good/"
```

**2. Relative URL**

```javascript
   Link from home page to product page
   href="t-shirts/t-shirt-life-is-good/"

   Link from product page to home page
   href="../../"
```

**_Note:_** In general, it is considered best-practice to use relative URLs, so that your website will not be bound to the base URL of where it is currently deployed. For example, it will be able to work on localhost, as well as on your public domain, without modifications.

**3. Protocol-relative URL**

```javascript
Link to home page
href="//paipixel.com/shop/"

Link to product page
href="//paipixel.com/shop/t-shirts/t-shirt-life-is-good/"
```

**_Note_**: It is a good choice if all pages are within the same domain. When you move your site to another domain, you don't have to do a mass replacements of the domain name in the URLs.

**4. Root-relative URL**
Relative to root folder of the domain.

```javascript
Link to home page
href="/shop/"

Link to product page
href="/shop/t-shirts/t-shirt-life-is-good/"
```

**_Note:_** It is a good choice if all pages are within the same domain. When you move your site to another domain, you don't have to do a mass replacements of the domain name in the URLs.

**5. Base-relative URL (home-page-relative)**
The tag `<base>` specifies the base URL, which is automatically added to all relative links and anchors. The base tag does not affect absolute links. As a base URL we'll specify the home page: `<base href="https://paipixel.com/shop/">`.

```javascript
Link to home page
href=""

Link to product page
href="t-shirts/t-shirt-life-is-good/"
```

**_Note:_** Now you can move your site not only to any domain, but in any subfolder. Just keep in mind that, although URLs look like relative, in fact they are absolute. Especially pay attention to anchors. To navigate within the current page we have to write `href="t-shirts/t-shirt-life-is-good/#comments"` not `href="#comments"`. The latter will throw on home page.

### Absolute URL versus Relative URL (Another Discussion)

```html
http://www.example.com/en/public/img/logo.gif \__/
\_____________/\_____________________/ #1 #2 #3
```

1. scheme/protocol
2. host
3. path

A _URL_ is called an absolute _URL_ if it begins with the scheme and scheme specific part (here `//` after `http:`). Anything else is a _relative URL_.

A _URL path_ is called an absolute _URL path_ if it begins with a `/`. Any other _URL path_ is called a _relative URL path_.

Thus:

- `http://www.example.com/en/public/img/logo.gif` is an _absolute URL_,
- `../../public/img/logo.gif` is a _relative URL_ with a _relative URL path_ and
- `/en/public/img/logo.gif` is a _relative URL_ with an _absolute URL path_.

Click to view the [Source Code](hyperlinks.html) which demonstrates all the examples above.

### Creating link to target a section/article on the same page

[Click Here](hyperlinks.html) to view the source code.

### Creating link to jump in Top

[Click Here](hyperlinks.html) to view the source code.

**References:**

- https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks
- https://stackoverflow.com/questions/2005079/absolute-vs-relative-urls
- https://stackoverflow.com/questions/904046/absolute-urls-relative-urls-and
- https://www.w3schools.com/html/html_links.asp
- https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Generic_syntax

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-11: CSS Position, Z-index, Overflow

- [CSS Position](#css-position)
  - [Position Property Values](#position-property-values)
  - [Static](#static)
  - [Absolute](#absolute)
  - [Fixed](#fixed)
  - [Relative](#relative)
  - [Sticky](#sticky)
- [CSS Z-index Property](#css-z-index-property)
  - [How Z-index Works](#how-z-index-works)
- [CSS Overflow](#css-overflow)
  - [How CSS Overflow Property Works](#how-css-overflow-property-works)
  - [Example of CSS Overflow Property](#example-of-css-overflow-property)

## CSS Position

### Position Property Values

| **Value** |                                                                                                                                                                                                **Description**                                                                                                                                                                                                 |
| :-------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  static   |                                 Default Value. অর্থাৎ কোন Element এর যদি কোন position property না দেয়া হয়, তাহলে by default, static সেট হয়ে যায়। এই Property এর বৈশিষ্ট্য হলো, element টি যে order এ আছে, সেই order এ document এ render এবং position সেট হবে। কোন Element এর Position Static থাকা অবস্থায় ওই Element এ Left, Right, Top, Bottom এর Property গুলো কাজ করবে না।                                  |
| absolute  |                                                                       The element is positioned relative to its first positioned (not static) ancestor element. অর্থাৎ position absolute একা একা কাজ করতে পারে না, তাকে কোন একটা Parent Element এর Under এ থাকতে হয়, এবং ওই Parent Element এর Position থেকে সে তার Position Change করে।                                                                        |
|   fixed   |                                                                                      The element is positioned relative to the browser window. এবং element টি একেবারে Fixed থাকে, আমার Document এ হাজার হাজার লাইন Text ও থাকে, তাহলেও fixed element তার Position কোনমতেও Change করবে না। একেবারে ঘারত্যারা যাকে বলে ! :D                                                                                      |
| relative  |                                   The element is positioned relative to its normal position, so "left:20px" adds 20 pixels to the element's left position. অর্থাৎ Relative Element স্বাধীন। তাকে কোন Parent Element এর Under এ থাকতে হবে বিষয় টা সেরকম নয়। যখনি কোন Element এর Property Relative করা হবে, তখন ওই Element এ Left, Right, Top, Down Properties গুলো কাজ করবে।                                    |
|  sticky   | যদি element এ top: 100px; দেয়া হয়, তাহলে এই element যে Position এ Normally থাকার কথা সেই Position এই থাকবে, কিন্তু Users Scroll করে ওই Position এর নিচে চলে যাবে, তখন এই Sticky element ও সাথে সাথে নিচে চলে যাবে। আর যখন নিচে যাবে তখন top থেকে 100px নিচে থাকবে। Fixed আর Sticky কখনই এক নয়। Fixed হলে element টি তার Normal Position এ না থেকে তার Parent Element থেকে Left, Right, Top, Bottom Count করবে। |

### Static

Default Value. অর্থাৎ কোন Element এর যদি কোন position property না দেয়া হয়, তাহলে by default, static সেট হয়ে যায়। এই Property এর বৈশিষ্ট্য হলো, element টি যে order এ আছে, সেই order এ document এ render এবং position সেট হবে। কোন Element এর Position Static থাকা অবস্থায় ওই Element এ Left, Right, Top, Bottom এর Property গুলো কাজ করবে না।
তাই কোন Element এ Static Property দেয়া না দেয়া একই কথা।

### Absolute

The element is positioned relative to its first positioned (not static) ancestor element. অর্থাৎ position absolute একা একা কাজ করতে পারে না, তাকে কোন একটা Parent Element এর Under এ থাকতে হয়, এবং ওই Parent Element এর Position থেকে সে তার Position Change করে।
অর্থাৎ কোন একটা Absolute Element এ যদি `left: 100px` দেয়া হয়, তাহলে ওই Element টি তার Parent Element এর Left থেকে 100px সরে সরে যাবে। Absolute Property সারারনত ব্যবহার করা হয় যখন একটা Element কে আরেকটি Element এর ভিতরে নিয়ে কাজ করার প্রয়োজন পরে।

#### Example of Absolute Property

[Open Project in CodePen](https://codepen.io/travelerabdulalim/pen/vYjOJWd)

### Fixed

The element is positioned relative to the browser window. এবং element টি একেবারে Fixed থাকে, আমার Document এ হাজার হাজার লাইন Text ও থাকে, তাহলেও fixed element তার Position কোনমতেও Change করবে না। একেবারে ঘারত্যারা যাকে বলে ! :D
Fixed Propertyও Absolute এর মত কোন একটা Parent Element এর Child হিসেবে থাকে।

#### Example of Fixed Property

[Open Project in CodePen](https://codepen.io/travelerabdulalim/pen/oNdXeEe)

### Relative

The element is positioned relative to its normal position, so "left:20px" adds 20 pixels to the element's left position. অর্থাৎ Relative Element স্বাধীন। তাকে কোন Parent Element এর Under এ থাকতে হবে বিষয় টা সেরকম নয়। যখনি কোন Element এর Property Relative করা হবে, তখন ওই Element এ Left, Right, Top, Down Properties গুলো কাজ করবে।

#### Example of Relative Property

[Open Project in CodePen](https://codepen.io/travelerabdulalim/pen/dyeozmZ)

### Sticky

যদি element এ top: 100px; দেয়া হয়, তাহলে এই element যে Position এ Normally থাকার কথা সেই Position এই থাকবে, কিন্তু User যখন Scroll করে ওই Position এর নিচে চলে যাবে, তখন এই Sticky element ও সাথে সাথে নিচে চলে যাবে। আর যখন নিচে যাবে তখন top থেকে 100px নিচে থাকবে। Fixed আর Sticky কখনই এক নয়। Fixed হলে element টি তার Normal Position এ না থেকে তার Parent Element থেকে Left, Right, Top, Bottom Count করবে।

অপরপক্ষে, Sticky Element এ যদি bottom: 100px; দেয়া হয় তাহলে Element টি যে Position এ Normally থাকার কথা সেই Position এই থাকবে, কিন্তু User যখন Scroll করে ওই Position এর উপরে
চলে যাবে, তখন এই Sticky Element ও সাথে সাথে উপরে চলে যাবে।

#### Example of Sticky Property

[Open Project in CodePen](https://codepen.io/travelerabdulalim/pen/abGOyjJ)

## CSS Z-index Property

### How Z-index Works

- The `z-index` property specifies the stack order of an element. An element can have a positive or negative stack order.
- z-index only works on `positioned elements` (position: absolute, position: relative, position: fixed, or position: sticky) and `flex items` (elements that are direct children of display: flex elements).
- An element with greater stack order is always above an element with a lower stack order. অর্থাৎ যে Element এর Z-index যত বেশি সে Element Stack এর তত উপরে থাকবে।

### Example of Z-index Property

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/jOxPQGZ)

## CSS Overflow

### How CSS Overflow Property Works

- The CSS `overflow` property controls what happens to content that is too big to fit into an area.
- The overflow property has the following values:

  - `visible` - Default. The overflow is not clipped. The content renders outside the element's box.
  - `hidden` - The overflow is clipped, and the rest of the content will be invisible.
  - `scroll` - The overflow is clipped, and a scrollbar is added to see the rest of the content.
  - `auto` - Similar to scroll, but it adds scrollbars only when necessary.

- Setting the overflow value to scroll, the overflow is clipped and a scrollbar is added to scroll inside the box. Note that this will add a scrollbar both horizontally and vertically (even if you do not need it).

### Example of CSS Overflow Property

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/MWGaJXB)

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-12: CSS Float, Display, Alignment

- [CSS Float](#css-float-property)
  - [CSS Float Property](#css-float-property)
  - [Example of CSS Float Property](#example-of-css-float-property)
  - [Another Example of CSS Float Property](#another-example-of-css-float-property)
  - [Clear Property](#clear-property)
  - [Example of Clear Property](#example-of-css-clear-property)
  - [Clearfix Hack](#clearfix-hack)
  - [Example of CSS Clearfix Hack](#example-of-css-clear-property)
- [CSS Display](#css-display-property)
  - [Basic Concepts of Inline-block](#basic-concepts-of-inline-block)
  - [Inline, Block and Inline-block Examples](#inline-block-and-inline-block-examples)
- [CSS Alignment of Elements, Texts and Images](#css-alignment-of-elements-texts-and-images)
  - [How to Center A Block Element](#how-to-center-a-block-element)
  - [How to Center Texts Inside An Element](#how-to-center-texts-inside-an-element)
  - [How to Center an Image](#how-to-center-an-image)
  - [How to Align an Element - Using Position](#how-to-align-an-element---using-position)
  - [CSS Alignment Examples](#css-alignment-examples)

## CSS Float Property

**Note: CSS Float Property is now deprecated in modern programming concept.**

The `float` property is used for positioning and formatting content e.g. let an image float left to the text in a container. The float property can have one of the following values:

- `left` - The element floats to the left of its container.
- `right` - The element floats to the right of its container.
- `none` - This is default. The element does not float (will be displayed just where it occurs in the text).
- `inherit` - The element inherits the float value of its parent.

The simplest use of `float` property is to to wrap text around images.

### Example of CSS Float Property

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/zYjvzXQ)

### Another Example of CSS Float Property

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/XWqmVVJ)

### Clear Property

When we use the `float` property, and we want the next element below (not on right or left), we will have to use the `clear` property.
The `clear` property specifies what should happen with the element that is next to a floating element.
The `clear` property can have one of the following values:

- This is default. `none` - The element is not pushed below left or right floated elements.
- `left` - The element is pushed below left floated elements.
- `right` - The element is pushed below right floated elements.
- `both` - The element is pushed below both left and right floated elements. This is safe to use when you are in a confusion between `left` and 'right'.
- `inherit` - The element inherits the clear value from its parent.

### Clearfix Hack

If a floated element is taller than the containing element, it will "overflow" outside of its container. We can then add a clearfix hack to solve this problem.
The overflow: auto clearfix works well as long as you are able to keep control of your margins and padding (else you might see scrollbars). The new, modern clearfix hack however, is safer to use, and the following code is used for most webpages.

### Example of CSS Clear Property

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/QWrjMJP)

## CSS Display Property

### Basic Concepts of Inline-block

- Compared to `display: inline`, the major difference is that `display: inline-block` allows to set a width and height on the element.
- Also, with `display: inline-block`, the top and bottom margins/paddings are respected, but with `display: inline` they are not.
- Compared to `display: block`, the major difference is that `display: inline-block` does not add a line-break after the element, so the element can sit next to other elements.
- 'display: inline' Property দিলে তখন height ও width property দিলেও কাজ করবে না। 'display: inline-block' ও 'display: block' Property তে height ও width property কাজ করবে। তবে, যখন 'display: block' দেয়া হবে তখন ওই Element টি পুরো লাইন জুরে জায়গা নিবে। নিচের উদাহরণ টি দেখলেই বিষয়টি পরিষ্কার হয়ে যাবে।

The following example shows the different behavior of `display: inline`, `display: inline-block` and `display: block`:

### Inline, Block and Inline-block Examples

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/XWqmBYy)

## CSS Alignment of Elements, Texts and Images

### How to Center A Block Element

- To horizontally center a block element (like `<div>`, `<h1>`, `<p>`), use `margin: auto`;
- **Note:** Center aligning has no effect if the width property is not set (or set to 100%).

### How to Center Texts Inside An Element

- To center the text inside an element, use `text-align: center;`

### How to Center an Image

- To center an image, set left and right margin to `auto` and make it into a `block` element:

### How to Align an Element - Using Position

- One method for aligning elements is to use `position: absolute;`
- **Note:** Absolute positioned elements are removed from the normal flow, and can overlap elements.
- Another method for aligning elements is to use the `float` property.

### CSS Alignment Examples

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/BaxjQoG)

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-13: CSS Flexbox

- [CSS Flexbox](#css-flexbox)
  - [CSS Flexbox Layout Module](#css-flexbox-layout-module)
  - [Flexbox Elements](#flexbox-elements)
  - [CSS Flexbox Tips](#tips)
  - [Flex Direction](#flex-direction)
  - [Flex Direction Example](#flex-direction-example)
  - [Justify Content Property in Flex](#justify-content-property-in-flex)
  - [Justify Content Property in Flex Example](#justify-content-property-in-flex-example)
  - [Align Items Property in Flex](#align-items-property-in-flex)
  - [Align Items Property in Flex Example](#align-items-property-in-flex-example)
- [The CSS Flexbox Container Properties Summary](#the-css-flexbox-container-properties-summary)

## CSS Flexbox

### CSS Flexbox Layout Module

Before the Flexbox Layout module, there were four layout modes:

1. Block, for sections in a webpage.
2. Inline, for text.
3. Table, for two-dimensional table data.
4. Positioned, for explicit position of an element.

**Note:** The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

### Flexbox Elements

- To start using the Flexbox model, you need to first define a flex container. অর্থাৎ Flexbox Model নিয়ে কাজ করতে হলে আমাদের প্রথম যে কাজটি করতে হবে তা হলো একটি Flex Container তৈরি করা।
- একটা Flex Model এর অবশ্যই একটা Flex Container থাকবে অর্থাৎ Flex Items গুলো একটা Parent Element ( যাকে Flex Containerও বলে) থাকবে। এবং ওই Flex Container/Parent Element এর **_display_** property এর Value **_flex_** থাকবে।
- Flex Container এর যারা Direct Child তারা Automatically **_Flex items_** হয়ে যাবে।

নিচে একটি Flex Container তৈরি করে দেখানো হলোঃ

![Flex Container](./day-13-css-flexbox/images/flex-container.png)

এখানে Flex Container হলো Blue Area Element. এবং তিনটি Flex Items হলো 1, 2 এবং 3.

Example: [Open in CodePen](https://codepen.io/travelerabdulalim/pen/xxjZLrx)

#### Tips

- Using **_rem_** is good practice than using **_px_**.
- Using **_float_** is deprecated in modern programming. Use **_flexbox_** instead.

### Flex Direction

`flex` has the following direction values:

- `flex: row;`
- `flex: row-reverse;`
- `flex: column;`
- `flex: column-reverse;`

`flex-wrap` has the following values:

- `flex-wrap: wrap;`
- `flex-wrap: no-wrap;`
- `flex-wrap: wrap-reverse;`

**Note:** The `flex-flow` property is a shorthand property for setting both the `flex-direction` and `flex-wrap` properties. Example: `flex-flow: row wrap;`

### Flex Direction Example

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/yLjepNq)

### Justify Content Property in Flex

- The `justify-content: center;` aligns the flex items at the center of the container.
- The `justify-content: flex-start;` aligns the flex items at the beginning of the container (this is default).
- The `justify-content: flex-end;` aligns the flex items at the end of the container.
- The `justify-content: space-around;` displays the flex items with space before, between, and after the lines.
- The `justify-content: space-between;` displays the flex items with space between the lines.

![center](./day-13-css-flexbox/images/center.png)
![flex start](./day-13-css-flexbox/images/flex-start.png)
![flex end](./day-13-css-flexbox/images/flex-end.png)
![space around](./day-13-css-flexbox/images/space-around.png)
![space between](./day-13-css-flexbox/images/space-between.png)

### JUSTIFY CONTENT Property in Flex Example

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/abGNoMy)

### ALIGN ITEMS Property in Flex

- The align-items property is used to align the flex items.
- The `align-items: center;` aligns the flex items in the middle of the container.
- The `align-items: flex-start;` aligns the flex items at the top of the container.
- The `align-items: flex-end;` aligns the flex items at the bottom of the container.
- The `align-items: stretch;` stretches the flex items to fill the container (this is default).
- The `align-items: baseline;` aligns the flex items such as their baselines aligns.

![align-items: center](./day-13-css-flexbox/images/align-center.png)
![align-items: flex start](./day-13-css-flexbox/images/align-flex-start.png)
![align-items: flex end](./day-13-css-flexbox/images/align-flex-end.png)
![align-items: baseline](./day-13-css-flexbox/images/align-baseline.png)

### ALIGN ITEMS Property in Flex Example

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/zYjqxdQ)

### The CSS Flexbox Container Properties Summary

|  **Property**   |                                                             **Description**                                                              |
| :-------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
|  align-content  | Modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines. |
|   align-items   |                    Vertically aligns the flex items when the items do not use all available space on the cross-axis.                     |
|     display     |                                           Specifies the type of box used for an HTML element.                                            |
| flex-direction  |                                  Specifies the direction of the flexible items inside a flex container.                                  |
|    flex-flow    |                                          A shorthand property for flex-direction and flex-wrap.                                          |
|    flex-wrap    |               Specifies whether the flex items should wrap or not, if there is not enough room for them on one flex line.                |
| justify-content |                    Horizontally aligns the flex items when the items do not use all available space on the main-axis.                    |

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-19: Visualize and Play with CSS Properties

Very Very helpful link to visualize, practice and play with css properties.
Link: https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-template
Credit: W3Schools

Note: Practice the properties as more as you can!

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-20: CSS Grid Layout

- [A Sample Example of CSS Grid Layout Module](#a-sample-example-of-css-grid-layout-module)
- [Basic Concept And Benefits of CSS Grid Layout](#basic-concept-and-benefits-of-css-grid-layout)
- [Grid Elements](#grid-elements)
- [All CSS Grid Properties](#all-css-grid-properties)
- [CSS Grid Layout Example-01](#css-grid-layout-example-01)
- [Full Responsive with Auto-fit and Minmax in Grid](#full-responsive-with-auto-fit-and-minmax-in-grid)
- [CSS Grid Tips](#css-grid-tips)
- [Visualize and Play with Grid Properties](#visualize-and-play-with-grid-properties)

### A Sample Example of CSS Grid Layout Module

![CSS Grid Layout Module](./day-20-css-grid-layout/images/css-grid-layout.png)

### Basic Concept And Benefits of CSS Grid Layout

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
- CSS Grid Layout এ Multidimensional Layout অর্থাৎ একইসাথে Row and Column নিয়ে কাজ করা যায়, যেখানে CSS Flexbox হলো One Dimensional, অর্থাৎ শুধু Row বা শুধু Column নিয়ে কাজ করা যায়।
- Simpler Markup.
- Framework not needed. অর্থাৎ শুধু Multi-dimensional Grid তৈরি করার জন্য কোন Framework ব্যবহার করার দরকার নেই, এই কাজ CSS Grid দিয়ে খুব সহজেই করে ফেলা যায়।
- Great Browsers Support.
- CSS Grid এক কথায় CSS Flexbox এর বাবা ! :D কারন CSS Grid দিয়ে আমরা Flexbox এর সমস্ত কিছু তো করতে পারবই, plus আরও অনেক Features আমরা ব্যবহার করতে পারবো, বিশেষ করে 2-dimensional (row and column both) Scenario এর ক্ষেত্রে CSS Grid খুব ভালো একটা সমাধান।

### Grid Elements

- A grid layout consists of a parent element (Grid Container), with one or more child elements. অর্থাৎ একটা Grid Layout এর একটা Parent Element বা Grid Container থাকবে, Grid Container এর Under এ একাধিক Grid Elements থাকবে।
- একটা Grid Layout তৈরি করতে Grid Container এর CSS Property তে `display: grid;` অথবা `display: inline-grid` দিতে হবে।

### All CSS Grid Properties

|       **Property**        |                                         **Syntax**                                          |                                                                                                                                                                                                                                                                                                                                                                                                      **Description**                                                                                                                                                                                                                                                                                                                                                                                                       |
| :-----------------------: | :-----------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      **column-gap**       |                        column-gap: length\|normal\|initial\|inherit;                        |                                                                                                                                                                                                                                                                                                                                                                   The column-gap property sets the gap between the columns. Example: `column-gap: 50px;`                                                                                                                                                                                                                                                                                                                                                                   |
|        **row-gap**        |                         row-gap: length\|normal\|initial\|inherit;                          |                                                                                                                                                                                                                                                                                                                                                                       The row-gap property sets the gap between the rows. Example: `row-gap: 50px;`                                                                                                                                                                                                                                                                                                                                                                        |
|          **gap**          |                                  gap: row-gap column-gap;                                   |                                                                                                                                                                                                                                                                                                                                                     The gap property is a shorthand property for the row-gap and the column-gap properties. Example: `gap: 25px 50px;`                                                                                                                                                                                                                                                                                                                                                     |
|  **gird-template-rows**   |     grid-template-rows: none\|auto\|max-content\|min-content\|length\|initial\|inherit;     |                                                                               The `grid-template-rows` property specifies the number and the heights of the rows in a grid layout. Example-01: `grid-template-rows: 50px 100px 70px 120px 150px;` Here, there are 5 rows. 1st row size is 50px, 2nd row size is 100px, 3rd row size is 70px, 4th row size is 120px and 5th row size is 150px. Example-02: `grid-template-rows: auto auto auto;`, means there are 3 rows with equal row size depending on the Grid Containers Height. Example-03: `grid-template-rows: 1fr 2fr 1fr;` , এর অর্থ হলো পুরো আমাদের Window টাকে ৪ ভাগ করবে, ১ ভাগ দিবে প্রথম Row কে, ২ ভাগ দিবে দ্বিতীয় Row কে এবং ১ ভাগ দিবে তৃতীয় Row কে । এটা 100% Responsive.                                                                                |
| **grid-template-columns** |   grid-template-columns: none\|auto\|max-content\|min-content\|length\|initial\|inherit;    |                                                              The `grid-template-columns` property specifies the number and the heights of the columns in a grid layout. Example-01: `grid-template-rows: 50px 100px 70px 120px 150px;` Here, there are 5 columns. 1st column size is 50px, 2nd column size is 100px, 3rd column size is 70px, 4th column size is 120px and 5th column size is 150px. Example-02: `grid-template-columns: auto auto auto;`, means there are 3 columns with equal column size depending on the Grid Containers Width. Example-03: `grid-template-columns: 3fr 2fr 3fr` , এর অর্থ হলো পুরো Window টাকে ৮ ভাগে ভাগ করবে, ৩ ভাগ দিবে প্রথম Column কে, ২ ভাগ দিবে দ্বিতীয় কলামকে এবং ৩ ভাগ দিবে তৃতীয় কলামকে। এটা 100% Responsive.                                                               |
|    **grid-row-start**     |                           grid-row-start: auto\|row-line\|span n;                           | একটা Grid Element কতো নাম্বার Row-line থেকে শুরু হবে সেটা বলে দেয়া হয় এই প্রপার্টি দ্বারা। এছাড়া একটা Grid Element কতোগুলো Row এর যায়গা নিজে একাই দখল করবে সেটাও বলে দেয়া যায় এই Property দ্বারা। Example-01: `grid-row-start: auto;` এটা By default Property. অর্থাৎ যে Grid Element এই Property set করে দেয়া হোক না কেন, প্রথম Grid Element থেকেই Grid Render হওয়া শুরু করবে। Example-02: `grid-row-start: span 3;` , এই প্রপার্টি যদি 2 নং Grid Element কে দেয়া হয়, তাহলে 2 নং Grid Element তিনটা Row এর সমান যায়গা দখল করবে। Example-03: `grid-row-start: 2;` এই প্রপার্টি যদি 3 নং Grid Element কে দেয়া হয়, তাহলে 3 নং Grid Element 2 নং Row-line এর শুরুতে বসে যাবে। বিষয়টি আরও ভালোভাবে বুঝতে নিচের W3 Schools লিঙ্কটি খুবই কার্যকরী। https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-row-start |
|     **grid-row-end**      |                            grid-row-end: auto\|row-line\|span n;                            |                                                                                                                                                                                                                                                                           Example-01: `grid-row-end: 3;` , এই প্রপার্টি যদি 2 নং Grid Element কে দেয়া হয়, তাহলে 2 নং Grid Element 3 নং Row-line এ End হবে। আরও ভালোমতো Practice and Visualize করতে নিচের লিঙ্কে যাওঃ https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-row-end                                                                                                                                                                                                                                                                           |
|   **grid-column-start**   |                        grid-column-start: auto\|span n\|column-line;                        |                                                                                                                                                                                            The grid-column-start property defines on which column-line the item will start. Example-01: `grid-column-start: 3;`, এই প্রপার্টি যদি ২ নং গ্রিড ইলেমেন্টকে দেয়া হয়, তাহলে সেই গ্রিড ইলেমেন্ট ৩ নং Column-line এ বসে যাবে। তাহলে ২ নং গ্রিড এর জন্য যে নির্ধারিত স্থান ছিলো সেটা কি হবে? সেই স্থান ফাঁকা থাকবে। নিচের লিঙ্কে ভিজুয়ালাইজ করে দেখো : https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-column-start                                                                                                                                                                                            |
|    **grid-column-end**    |                         grid-column-end: auto\|span n\|column-line;                         |                                                                                                                                                                                                          The grid-column-end property defines how many columns an item will span, or on which column-line the item will end. Example-01: `grid-column-end: 3;` এই প্রপার্টি যদি ১ নং গ্রিড ইলেমেন্টকে দেয়া হয়, তাহলে ১ নং গ্রিড ইলেমেন্ট ৩ নং Column-line এ End হবে। নিচের লিংকে ভিজিট করে নিজে নিজে Visualize করে দেখোঃ https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-column-end&preval=5                                                                                                                                                                                                           |
|       **grid-row**        |                          grid-row: grid-row-start / grid-row-end;                           |                                                                                                                                                                                                                                                                                                                                         Example-01: `grid-row: 1 / 3`, অর্থাৎ যে Element এ এই Property দেয়া হবে, সেই Element টি ১ নং row-line এ শুরু হবে, ৩ নং row-line এ শেষ হবে।                                                                                                                                                                                                                                                                                                                                         |
|      **grid-column**      |                      grid-column: grid-column-start / grid-column-end;                      |                                                                                                                                                                                                                                                                                                                                    Example-01: `grid-column: 1 / 3`, অর্থাৎ যে Element এ এই Property দেয়া হবে, সেই Element টি ১ নং column-line এ শুরু হবে, ৩ নং column-line এ শেষ হবে।                                                                                                                                                                                                                                                                                                                                     |
|       **grid-area**       | grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end \| itemname; |                                                                                                                                                                                                                                                                                                                                                                                                Example-01: `grid-area: h;`                                                                                                                                                                                                                                                                                                                                                                                                 |
|  **grid-template-areas**  |                            grid-template-areas: none\|itemnames;                            |                                                                                                                                                                                                                                                                                                                                                     Example-01: `grid-template-areas: "m h h h h h h h h h h h" "m c c c c c c c c c c c" "f f f f f f f f f f f f";`                                                                                                                                                                                                                                                                                                                                                      |
|    **justify-content**    |       justify-content: start\|end\|center\|space-between\|space-around\|space-evenly;       |                                                                                                                                                                                                                                                                                                                               Example-01: `justify-content: center;` এই Property যখন কোন Container কে দেয়া হবে, তখন ঐ Container এ যতগুলো Items থাকবে তারা সব Horizontally Center এ চলে যাবে।                                                                                                                                                                                                                                                                                                                               |
|     **align-content**     |        align-content: start\|end\|center\|space-between\|space-around\|space-evenly;        |                                                                                                                                                                                                                                                                                                                                 Example-01: `align-content: center;` এই Property যখন কোন Container কে দেয়া হবে, তখন ঐ Container এ যতগুলো Items থাকবে তারা সব Vertically Center এ চলে যাবে।                                                                                                                                                                                                                                                                                                                                 |

### CSS Grid Layout Example-01

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/rNvLeXL)

### Full Responsive with Auto-fit and Minmax in Grid

[Open Live Project in CodePen](https://codepen.io/travelerabdulalim/pen/gOzMMvN)

### CSS Grid Tips

- Shorthand property of `grid-template-rows` and `grid-template-columns` is `grid-template: `grid-template-rows / grid-template-columns`.
- যদি আমরা `grid-template-rows: 1fr 1fr 1fr 1fr 1fr` দিতে চাই, তাহলে এইভাবে ৫ বার না লিখে সংক্ষেপে `grid-template-rows: repeat(5, 1fr)` দিতে পারি।

### Visualize and Play with Grid Properties

[Visualize and Play with Grid Properties](https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_grid-template-rows)
Credit: W3Schools

[<h3 align="center">Go to Top</h3>](#learn-html-and-css-in-30-days)

# Day-21: CSS Gradient, Shadows, Text Effects and Web Fonts

- [CSS Gradients](#css-gradients)

## CSS Gradients

### Basic Concepts of CSS Gradients

- CSS gradients let you display smooth transitions between two or more specified colors.

### Types of Gradients

1. Linear Gradients (goes down/up/left/right/diagonally).
2. Radial Gradients (defined by their center).
3. Conic Gradients (rotated around a center point).

### Linear Gradients

- Linear Gradients তৈরি করতে অন্তত ২ টি Colors লাগবে। ধরি, `background-image: linear-gradient(red, blue);` তাহলে লাল রং থেকে নীল রং Transition হবে, উপর থেকে নিচ বরাবর (Top to Bottom), যেটা By default প্রপার্টি, আমরা চাইলে এই By default প্রপার্টিকে পরিবর্তন করতে পারি।

### Syntax of Linear Gradients

`background-image: linear-gradient(direction, color-stop1, color-stop2, ...);`

### Direction of Linear Gradients

- Linear Gradient এর কাজটা হলো একটা Color থেকে ধীরে ধীরে আরেকটা Color তৈরি করা, যেটাকে ইংরেজিতে Transition বলা হচ্ছে। এখন কোন একটা Color কোথা থেকে শুরু করে কোথায় গিয়ে দ্বিতীয় Color এ Transition হবে সেটা আমরা `Direction` এর মাধ্যমে বলে দিতে পারি।

### Direction - Top to Bottom (this is default )

- অর্থাৎ আমরা যদি কোন Direction না দেই, তাহলে by default, Top to Bottom এ Transition হবে।

Example: `background-image: linear-gradients(red, yellow);` . This linear gradient starts red, transitioning to yellow.

Output Screenshot: ![Top to Bottom](./day-21-css-gradients-shadows-text-effects-web-fonts/images/to-to-bottom.png)

### Direction - Left to Right

Example: `background-image: linear-gradients(to right, red, yellow);`
The following example shows a linear gradient that starts from the left. It starts red, transitioning to yellow.

Output Screenshot:
![Left to Right](./day-21-css-gradients-shadows-text-effects-web-fonts/images/left-to-right.png)

### Direction - Top Left to Bottom Right

Example: `background-image: linear-gradients( to bottom right, red, yellow);`
The following example shows a linear gradient that starts at top left (and goes to bottom right). It starts red, transitioning to yellow.

Output Screenshot:
![Topleft to Bottomright](./day-21-css-gradients-shadows-text-effects-web-fonts/images/topleft-to-bottomright.png)

### Direction - 180deg

যদি Direction এর উপর আমরা আরও বেশি Control নিতে চাই, তাহলে আমাদের যে Pre-defined Directions (to bottom, to top, to right, to left, to bottom right, etc.) আছে, এগুলোর বদলে আমরা Angle ব্যবহার করতে পারি। A value of 0deg is equivalent to "to top". A value of 90deg is equivalent to "to right". A value of 180deg is equivalent to "to bottom".
Example: `background-image: linear-gradient(180deg, red, yellow);`
Output Screenshot:
![180deg](./day-21-css-gradients-shadows-text-effects-web-fonts/images/180deg.png)

### Direction - 90deg

Example: `background-image: linear-gradient(90deg, red, yellow);`
Output Screenshot:
![](./day-21-css-gradients-shadows-text-effects-web-fonts/images/90deg.png)

### Direction - 0% x% 100%

Example: `background-image: linear-gradient(#feffff 0%, #ddf1f9 35%, #a0d8ef 100%);`

Output Screenshot:
![Percentage 1](./day-21-css-gradients-shadows-text-effects-web-fonts/images/percentage1.png)

### Direction - 20% 70%

Example: `background-image: linear-gradient(red 20%, yellow 70%);` এর অর্থ হলো ০ থেকে ২০% Red Color থাকবে, ৭০% থেকে ১০০% Yellow Color থাকবে, বাকি থাকলো ২১% থেকে ৬৯%, এইটুকু Red থেকে Yellow তে Transition হবে।

Output Screenshot:
![Percentage 1](./day-21-css-gradients-shadows-text-effects-web-fonts/images/percentage2.png)

### Direction - 50% 50%

Example: `background-image: linear-gradient(to top right, red 50%, yellow 50%);`

খেয়াল করে দেখুন, এখানে ০ থেকে ৫০% পর্যন্ত red color এবং ৫০% থেকে ১০০% পর্যন্ত yellow color থাকবে, কিন্তু Transition হবার মতো কোন যায়গা নেই।

Output Screenshot:
![Percentage 3](./day-21-css-gradients-shadows-text-effects-web-fonts/images/percentage3.png)

### Direction - 20% 20%-80% 80%

Example: `background-image: linear-gradient(to top right, red 20%, green 20% 80%, red 80%);`

### Using Transparency as Direction

অর্থাৎ এখানে আসলে একটা Color ই থাকবে যার Value একদম ০ থেকে বাড়তে বাড়তে ১০০% হবে। এক্ষেত্রে আমরা rgba() function ব্যবহার করতে পারি, এই Function এর Last Parameter এ 0 দেওয়া মানে Full Transparency, 1 দেওয়া মানে Full Color (No Transparency).

Example: `background-image: linear-gradient(to right, rgba(255,0,0,0), rgba(255,0,0,1));`

Output Screenshot:
![Transparency](./day-21-css-gradients-shadows-text-effects-web-fonts/images/transparency.png)

### Repeating a linear-gradient

Example: `background-image: repeating-linear-gradient(red, yellow 10%, green 20%);`
Output Screenshot:
![Repeating linear gradient](./day-21-css-gradients-shadows-text-effects-web-fonts/images/repeating.png)
