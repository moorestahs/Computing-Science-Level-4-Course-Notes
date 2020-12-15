---
title: "Web Page Structure"
draft: false
weight: 30
---

The HTML in a web page follows a basic structure.


The `<html>` tag is the first tag in the page and the closing tag is the last tag.

The `<head>` tag generally appears next and contains information about our page. In our practical tasks we place the `<title>` and `<link>` tags here to set the page title and link to the external stylesheet respectively.

The `<body>` tag is where the main page content goes. If you want something to appear on the screen then it needs to go inside this tag.

## Structure

The structure of the page looks like this. Note that the lines starting `<!--` are called __comment__ lines and are there to provide extra information.

```html
<html>
	<head>
		<!-- The page title and optional link to the stylesheet go here. -->
		<title> ... </title>
		<link rel="stylesheet" type="/text" src="styles.css">
	</head>
	<body>
		<!-- The main page content goes here. -->
	</body>
</html>
```
		
		