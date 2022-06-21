<h1 align="center"> Day-03: HTML Entities, Hyperlinks, Images, Audio, Videos </h1>

  - [HTML Entities](#html-entities)
  - [Hyperlinks](#hyperlinks)
  
  

### HTML Entities
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


### Hyperlinks
---
#### What is Hyperlinks?
Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address (URL).

#### HTML Link Syntax
The HTML `<a>` tag defines a hyperlink. It has the following syntax:
```html
 <a href="url">link text</a>
 ```
The most important attribute of the `<a>` element is the ***href*** attribute, which indicates the link's destination.

The **link text** is the part that will be visible to the reader. Clicking on the link text, will send the reader to the specified URL address.

##### Example:
```html
<a href="https://www.travelerabdulalim.com/">Visit My Travel Blog</a>
```
##### Output:
[Visit My Travel Blog](https://www.travelerabdulalim.com/)

#### HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.
The ***target*** attribute specifies where to open the linked document.
The **target** attribute can have one of the following values:

- `_self` : Default. Opens the document in the same window/tab as it was clicked.
- `_blank` : Opens the document in a new window or tab.
- `_parent` : Opens the document in the parent frame.
- `_top` : Opens the document in the full body of the window.

View the [Source Code](hyperlinks.html) to see the application of these attributes.

#### HTML Links - The title Attribute
The **title** contains additional information about the link, we can see the **title** text while hovering the link.

Click the [Source Code](hyperlinks.html) to view the application of **title** attribute.


#### Absolute URL vs. Relative URL

**Absolute URL:**
Points to a location defined by its absolute location on the web, including protocol and domain name.For example, if an `index.html` page is uploaded to a directory called `projects` that sits inside the **root** of a web server, and the website's domain is `https://www.example.com`, the page would be available at `https://www.example.com/projects/index.html`

An absolute URL will always point to the same location, no matter where it's used.

**Relative URL:**
Points to a location that is *relative* to the file you are linking from, more like what we looked at in the previous section. For example, if we wanted to link from our example file at `https://www.example.com/projects/index.html` to a PDF file in the same directory, the URL would just be the filename — `project-brief.pdf` — no extra information needed. If the PDF was available in a subdirectory inside `projects` called `pdfs`, the relative link would be `pdfs/project-brief.pdf`(the equivalent absolute URL would be `https://www.example.com/projects/pdfs/project-brief.pdf`)
[<h3 align="center">Go to Home Page</h3>](../README.md) 

[<h3 align="center">Go to DAY-02</h3>](../day-02-html-tags/DAY02.md)

[<h3 align="center">Go to DAY-04</h3>](../day-04-list-tables-containers/DAY04.md)