---
title: "CSS"
draft: false
weight: 40
---

CSS allows us to style our web page. There are three places where we can write CSS:

1. In an __external__ CSS file
2. In an __internal__ style block within the `<head>`
3. __Inline__, as an attribute of a tag

## CSS Syntax

CSS uses a different syntax to HTML. Syntax means the 'rules of the language'.

CSS is really just a list of rules that will apply to our HTML. The rules will can do things such as:

+ change the font used
+ change the colours and background colours
+ change the sizes of text
+ change the position of something on the screen

## CSS Selectors

Each rule starts with a __selector__ - The selector is the element that we want the rule to apply to. For now, our selectors will all be HTML tags. A rule that targets the `h1` tag would look like this:

```css
h1 {
	/* CSS Properties go here */
}
```

## CSS Properties

The properties are the things that we can change. There are hundreds of possible CSS properties that control many different aspects of how our elements look.

| Property| Description
| ------- | -----------
| font-family		| Used to change the font for an element. This can be serif, sans-serif or cursive.
| font-size			| Used to change the size of text. Text size should be given in a unit called em. 1em is about 16px.
| text-align		| Used to change the text alignment: left, right, centred, justified
| color				| Used to change the colour of text.
| background-color	| Used to change the colour of the background of an element. We will use this to change the page background.
| border			| Creates a border around an element which can be styled

