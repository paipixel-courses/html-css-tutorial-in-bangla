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
```
```

[<h3 align="center">Go to Home Page</h3>](../README.md) 

[<h3 align="center">Go to DAY-02</h3>](../day-02-html-tags/DAY02.md)

[<h3 align="center">Go to DAY-04</h3>](../day-04-list-tables-containers/DAY04.md)