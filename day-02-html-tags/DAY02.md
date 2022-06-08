<h1 align="center"> Day-02: Commonly Used HTML Tags & Their Usage </h1>

  - [&lt;em&gt;](#&lt;em&gt;)
  - [&lt;i&gt; vs &lt;em&gt;](#-i-vs-em)
  - [&lt;strong&gt;](#-strong)
  - [&lt;b&gt; vs &lt;strong&gt;](#-b-vs-strong)
  
  

### &lt;em&gt;
---
The **`<em>`** element is used to define emphasized text. By default, emphasized text is displayed in *italic*.   However, it should not be used to apply italic styling; use the CSS `font-style` property for that purpose. Use the `<cite>` element to mark the title of a work (book, play, song, etc.). Use the `<i>` element to mark text that is in an alternate tone or mood, which covers many common situations for italics such as scientific names or words in other languages. Use the `<strong>` element to mark text that has greater importance than surrounding text.<br>
Visit [HERE](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em) for learning more about this element.

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
        Cox’s Bazar is a town on the southeast coast of <em>Bangladesh</em>. 
    </article>
</body>
</html>
```
**Output:**
Cox’s Bazar is a town on the southeast coast of *Bangladesh*.


### &lt;i&gt; vs &lt;em&gt;
---
New developers are often confused at seeing multiple elements that produce similar results. `<em>` and `<i>` are a common example, since they both italicize text. What's the difference? Which should you use?

By default, the visual result is the same. However, the semantic meaning is different. The `<em>` element represents stress emphasis of its contents, while the `<i>` element represents text that is set off from the normal prose, such a foreign word, fictional character thoughts, or when the text refers to the definition of a word instead of representing its semantic meaning. (The title of a work, such as the name of a book or movie, should use `<cite>`.)

This means the right one to use depends on the situation. Neither is for purely decorative purposes, that's what CSS styling is for.

An example for `<em>` could be: "Just *do* it already!", or: "We *had* to do something about it". A person or software reading the text would pronounce the words in italics with an emphasis, using verbal stress.

An example for `<i>` could be: "The *Queen Mary* sailed last night". Here, there is no added emphasis or importance on the word "Queen Mary". It is merely indicated that the object in question is not a queen named Mary, but a ship named *Queen Mary*. Another example for `<i>` could be: "The word *the* is an article".

**Example:**
```html
<p>
  In HTML 5, what was previously called
  <em>block-level</em> content is now called
  <em>flow</em> content.
</p>
```

**Result/Output:**
In HTML 5, what was previously called *block-level* content is now called *flow* content.

Thanks [Mozilla Developer Network-MDN](https://developer.mozilla.org/en-US/docs/MDN/About) for [this awesome documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em).
### &lt;strong&gt;
---
The `<strong>` element indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.

The `<strong>` element is for content that is of "strong importance," including things of great seriousness or urgency (such as warnings). This could be a sentence that is of great importance to the whole page, or you could merely try to point out that some words are of greater importance compared to nearby content.

Typically this element is rendered by default using a bold font weight. However, it should not be used to apply bold styling; use the CSS `font-weight` property for that purpose. Use the `<b>` element to draw attention to certain text without indicating a higher level of importance. Use the `<em>` element to mark text that has stress emphasis.

Another accepted use for `<strong>` is to denote the labels of paragraphs which represent notes or warnings within the text of a page.

## &lt;b&gt; vs &lt;strong&gt;
---
It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. `<b>` and `<strong>` are perhaps one of the most common sources of confusion, causing developers to ask "Should I use `<b>` or `<strong>`? Don't they both do the same thing?"

Not exactly. The `<strong>` element is for content that is of greater importance, while the `<b>` element is used to draw attention to text without indicating that it's more important.

It may help to realize that both are valid and semantic elements in HTML5 and that it's a coincidence that they both have the same default styling (boldface) in most browsers (although some older browsers actually underline `<strong>`).

 Each element is meant to be used in certain types of scenarios, and if you want to bold text for decoration, you should instead actually use the CSS `font-weight` property.

 The intended meaning or purpose of the enclosed text should be what determines which element you use. Communicating meaning is what semantics are all about.

 ### &lt;em&gt; vs &lt;strong&gt;
 ---
 While `<em>` is used to change the meaning of a sentence as spoken emphasis does ("I *love carrots*" vs. "I love *carrots*"), `<strong>` is used to give portions of a sentence added importance (e.g., "**Warning**! This is **very dangerous**.") Both `<strong>` and `<em>` can be nested to increase the relative degree of importance or stress emphasis, respectively.

 ### Example:
 **Hope** is a good thing, maybe the best of things and no good thing ever dies. 


[Visit here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) to learn more.

