<h1 align="center"> Day-03: HTML Entities, Hyperlinks, Images, Audio, Videos </h1>

  - [HTML Entities](#html-entities)
  - [Hyperlinks](#hyperlinks)
  
  

## HTML Entities
---
Some characters are reserved in HTML. If you use the less than (<) or greater than (>) signs in your text, the browser might mix them with tags.
Character entities are used to display reserved characters in HTML.
***Here are the list of some HTML Entities:***
| Entity |            Description            | Entity Name |
|:------:|:---------------------------------:|:-----------:|
|        |         non-breaking space        | `&nbsp;`|             | 
|    <   |             less than             |     `&lt;`    |
|    >   |            greater than           |     `&gt;`    |
|    &   |             ampersand             |    `&amp;`    |
|    "   |       double quotation mark       |    `&quot;`   |
|    '   | single quotation mark(apostrophe) |    `&apos;`   |
|    £   |               pound               |   `&pound;`   |
|    €   |                euro               |    `&euro;`   |
|    ©   |             copyright             |    `&copy;`   |
|    ®   |       registered trademark        |    `&reg;`    |

**Note:** Entities names are case-sensitive.
Here is the [HTML](table.html) and [CSS](table.css) code that generates all the entites listed above.


## Hyperlinks
---
### What is Hyperlinks?
Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address (URL).

### HTML Link Syntax
The HTML `<a>` tag defines a hyperlink. It has the following syntax:
```html
 <a href="url">link text</a>
 ```
The most important attribute of the `<a>` element is the ***href*** attribute, which indicates the link's destination.

The **link text** is the part that will be visible to the reader. Clicking on the link text, will send the reader to the specified URL address.

#### Example:
```html
<a href="https://www.travelerabdulalim.com/">Visit My Travel Blog</a>
```
#### Output:
[Visit My Travel Blog](https://www.travelerabdulalim.com/)

### HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.
The ***target*** attribute specifies where to open the linked document.
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
Points to a location that is *relative* to the file you are linking from, more like what we looked at in the previous section. For example, if we wanted to link from our example file at `https://www.example.com/projects/index.html` to a PDF file in the same directory, the URL would just be the filename — `project-brief.pdf` — no extra information needed. If the PDF was available in a subdirectory inside `projects` called `pdfs`, the relative link would be `pdfs/project-brief.pdf`(the equivalent absolute URL would be `https://www.example.com/projects/pdfs/project-brief.pdf`)

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
   ***Note:*** In general, it is considered best-practice to use relative URLs, so that your website will not be bound to the base URL of where it is currently deployed. For example, it will be able to work on localhost, as well as on your public domain, without modifications.

  **3. Protocol-relative URL**
  ```javascript
  Link to home page
href="//paipixel.com/shop/"

Link to product page
href="//paipixel.com/shop/t-shirts/t-shirt-life-is-good/"
  ```
***Note***: It is a good choice if all pages are within the same domain. When you move your site to another domain, you don't have to do a mass replacements of the domain name in the URLs.

**4. Root-relative URL**
Relative to root folder of the domain.
```javascript
Link to home page
href="/shop/"

Link to product page
href="/shop/t-shirts/t-shirt-life-is-good/"
```
***Note:*** It is a good choice if all pages are within the same domain. When you move your site to another domain, you don't have to do a mass replacements of the domain name in the URLs.

**5.  Base-relative URL (home-page-relative)**
The tag `<base>` specifies the base URL, which is automatically added to all relative links and anchors. The base tag does not affect absolute links. As a base URL we'll specify the home page: `<base href="https://paipixel.com/shop/">`.

```javascript
Link to home page
href=""

Link to product page
href="t-shirts/t-shirt-life-is-good/"
```
***Note:*** Now you can move your site not only to any domain, but in any subfolder. Just keep in mind that, although URLs look like relative, in fact they are absolute. Especially pay attention to anchors. To navigate within the current page we have to write `href="t-shirts/t-shirt-life-is-good/#comments"` not `href="#comments"`. The latter will throw on home page.

### Absolute URL versus Relative URL (Another Discussion)

```html
http://www.example.com/en/public/img/logo.gif
\__/   \_____________/\_____________________/
 #1     #2             #3
```
1. scheme/protocol
2. host
3. path

A *URL* is called an absolute *URL* if it begins with the scheme and scheme specific part (here `//` after `http:`). Anything else is a *relative URL*.

A *URL path* is called an absolute *URL path* if it begins with a `/`. Any other *URL path* is called a *relative URL path*.

Thus:

- `http://www.example.com/en/public/img/logo.gif` is an  *absolute URL*,
- `../../public/img/logo.gif` is a *relative URL* with a *relative URL path* and
- `/en/public/img/logo.gif` is a *relative URL* with an *absolute URL path*.


**References:**

- https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks
- https://stackoverflow.com/questions/2005079/absolute-vs-relative-urls
- https://stackoverflow.com/questions/904046/absolute-urls-relative-urls-and
- https://www.w3schools.com/html/html_links.asp
- https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Generic_syntax
  

[<h3 align="center">Go to Home Page</h3>](../README.md) 

[<h3 align="center">Go to DAY-02</h3>](../day-02-html-tags/DAY02.md)

[<h3 align="center">Go to DAY-04</h3>](../day-04-list-tables-containers/DAY04.md)