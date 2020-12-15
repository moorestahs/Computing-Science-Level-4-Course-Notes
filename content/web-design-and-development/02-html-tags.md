---
title: "HTML - Tags"
draft: false
weight: 20
---

HTML consists of __tags__. There are about __100__ tags that make up HTML but you don't need to remember all of them to create websites - most websites are created with a much smaller number of tags.

## Tags

The majority of tags have an __opening__ part and a __closing__ part. The tags themselves are written inside angled brackets `< >`. For example the heading 1 tag which produces the largest text is called __h1__ and it's opening tag is `<h1>`.

Closing tags put a `/` before the name of the tag e.g. the closing h1 tag is `</h1>`. Therefore an example h1 heading in a web page would be written as:

```html
<h1>Welcome to Web Design and Development</h1>
```

There are a few tags that don't have closing tags. The `<img>` tag for adding an image is one common example of this.

### Tag Attributes

Sometimes there is some extra information written inside the opening tag. These are called __attributes__. Attributes provide extra information about the tag. You'll see examples of this later but a common one is the 'href' attribute in the anchor tag (`<a>`). The anchor tag is used to create hyperlinks and the href attribute provides the destination. Here's an example:

```html
<a href="https://www.wikipedia.org/">Click here to go to Wikipedia</a>
```

The `href` attribute is to `https://www.wikipedia.org/` and when the user clicks or taps on the text <a href="https://www.wikipedia.org/">Click here to go to Wikipedia</a> they will then go to the Wikipedia home page. Try it!

## Common Tags

Some common tags that we are using in our practical tasks include:

| Tag | Description
| --- | -----------
| html  | The first and last tag in our web page 
| head  | Provides information (metadata) about our web page
| link  | Adds the external stylesheet to our web page
| title	| Sets the page title in the browser window
| body  | The main content of our web page
| h1	| Largest heading
| p	    | Paragraphs
| h2	| Second largest heading
| img	| Add an image to the page
| ul    | Unordered list - creates a list using bullet pints
| ol    | Ordered list - creates a numbered list i.e. 1, 2, 3 etc.
| li	| An item in a list (either ordered or unordered)
| br	| A line break

## Creating Lists

To create an __unordered__ list we can do:

```html
<ul>
	<li>Item 1</li>
	<li>Item 2</li>
	<li>Item 3</li>
</ul>
```

which will produce the output:

+ Item 1
+ Item 2
+ Item 3

To create an __ordered__ list we can do:

```html
<ol>
	<li>Item 1</li>
	<li>Item 2</li>
	<li>Item 3</li>
</ol>
```

which will produce the output:

1. Item 1
2. Item 2
3. Item 3

