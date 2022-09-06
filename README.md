# Learn HTML and CSS in 30 Days

|                          **Day**                           |                                                **Topics**                                                |
| :--------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|                 [01](#day-01-introduction)                 |                                   [Introduction](#day-01-introduction)                                   |
|     [02](#day-02-commonly-used-html-tags--their-usage)     |                        [HTML Tags](#day-02-commonly-used-html-tags--their-usage)                         |
| [03](#day-03-html-entities-hyperlinks-images-audio-videos) | [HTML Entities, Hyperlinks, Images, Audio, Videos](#day-03-html-entities-hyperlinks-images-audio-videos) |
|                           [04]()                           |
|                             05                             |                                                                                                          |
|                             06                             |                                                                                                          |
|                             07                             |                                                                                                          |
|                             08                             |                                                                                                          |
|                             09                             |                                                                                                          |
|                             10                             |                                                                                                          |
|            [11](#day-11-css-position-property)             |                          [CSS Position Property](#day-11-css-position-property)                          |
|                             12                             |                                                                                                          |
|                             13                             |                                                                                                          |
|                             14                             |                                                                                                          |
|                             15                             |                                                                                                          |
|                             16                             |                                                                                                          |
|                             17                             |                                                                                                          |
|                             18                             |                                                                                                          |
|                             19                             |                                                                                                          |
|                             20                             |                                                                                                          |
|                             21                             |                                                                                                          |
|                             22                             |                                                                                                          |
|                             23                             |                                                                                                          |
|                             24                             |                                                                                                          |
|                             25                             |                                                                                                          |
|                             26                             |                                                                                                          |
|                             27                             |                                                                                                          |
|                             28                             |                                                                                                          |
|                             29                             |                                                                                                          |
|                             30                             |                                                                                                          |

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

# Day-11: CSS Position Property

- [Position Property Values](#position-property-values)

- [Static](#static)

- [Absolute](#absolute)
- [Fixed](#fixed)
- [Relative](#relative)
- [Sticky](#sticky)

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
