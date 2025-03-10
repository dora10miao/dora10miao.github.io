---
layout: post
title: Markdown Grammar
subtitle: 如何快速上手 markdown 语法？
gh-repo: daattali/beautiful-jekyll
tags: [test]
comments: true
---

<!-- # <center>Markdown Grammar</center> -->
source: *[Markdown Document](https://markdown.com.cn/basic-syntax/links.html#code)*

## Heading
\# `<h1></h1>`<br>
\## `<h2></h2>`<br>
...

## Paragraph
a blank line<br>
`<p></p>`

## Line Break
*<u>Method One: add br tag at the end.(Suggested)</u>*<br>
This is the first line.<br>And this is the second line.

*<u>Method Two: two spaces + Enter</u>*<br>
This is the third line.  
And this is the fourth line.

## Italic &  Bold
\*italic* `<i>italic</i>` or `<em>italic</em>`<br>
\*\*bold** `<b>bold</b>` or `<strong>bold</strong>`<br>
\*\*\*both italic and bold*** `<b><i>both italic and bold</i></b>`

## Blockquote
\> 
> blockquote

## OrderList
1.<br>
`<ol><li></li></ol>`

## UnorderList
\-<br>
`<ul><li></li></ul>`

## Code
\`\<p>\</p>\`<br>
`<p></p>`

## Fenced Code Blocks
Add **```html** at the beginning of the code.

Add **```** at the end.

```html
<div>This is a div tag</div>
```

## Horizental Line
\---

---

## Link
### Basic usage of link
\[Google](https://www.google.com "click to google")

\<a href="https://www.google.com" title="click to google">Google</a>

[Google](https://www.google.com "click to google")

### Reference type link
[hobbit-hole] [1]

<!-- endnotes or footnotes -->
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

## Picture
\![this is a pic]\(https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "magic garden")

\<img src="https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg" alt="this is a pic" title="magic garden">

![this is a pic](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "magic garden")

