<p align="center">
  <img src="banner.jpg">
  <h1 align="center">Textretty</h1>
  <p align="center">A simple typography stylesheet for article content.</p>
  <p align="center"><a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"></a> <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-green?style=flat-square"></a> <img src="https://img.shields.io/github/stars/BigCoke233/textretty.css?label=Star&style=flat-square"> <a href="https://github.com/BigCoke233/textretty/releases"><img src="https://img.shields.io/github/downloads/BigCoke233/textretty.css/total?style=flat-square"></a></p>
</p>

## Introduction

**Textretty** is a simple typography stylesheet which can be used on any html-based document. It's usually for article content but not the whole website. It can help you start writing quickly and you don't need to care about the style too much.
And it has referenced to GitHub Markdown style.

## Installation

Install `textretty` with npm.
```git
$ npm install textretty
```
Or you can just grab the css file in the `./dist` folder.

You can also get `textretty.css` with jsDelivr CDN, this method does not require to install.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/BigCoke233/textretty.css/dist/textretty.min.css">
```

## Usage

**Textretty** only works in the element with `.textretty` class.
```html
<head>
  <!-- ...... -->
  <link rel="stylesheet" href="textretty.css">
  <!-- ...... -->
</head>
<body>
  <!-- ...... -->
  <article class="textretty">
    <!-- your content here -->
  </article>
  <!-- ...... -->
</body>
```

## Standard

**Textretty** has its own standard for elements. This following table shows every defined html tag and its standard usage. You are supposed to follow them.

| Tag Name       | Descripiton |
| -------------- | ----------- |
| **h1-h6**      | Graded headings used as titles |
| **p**          | Paragraph   |
| **strong**, b  | Text in bold |
| **em**, i      | Text in italic |
| **del**, s     | Deleted text |
| **a**          | Anchor link |
| **img**        | Image       |
| **pre**        | Code block  |
| **code**       | Inline code |
| **kbd**        | Text on keyboards |
| **ol**         | Ordered list |
| **ul**         | Unordered list |
| **li**         | List item   |
| **table**      | Just table  |
| **tr**         | Rows of table |
| **th**         | Headings of table |
| **td**         | Cells of table |
| **thead**      | The header of a table |
| **tbody**      | The body content of a table |
| **tfoot**      | The footer of a table |
| **blockquote** | Quotions (block displayed) |
| **hr**         | Divider / Separator |
| **header**     | The header of an article/document |
| **footer**     | The footer of an article/document |

These tags above are all defined in `textretty.css`. 

### Headings

`<h1>`~`<h6>` are all headings. Usually, `<h1>` are used as the main title of the whole article / document. Others're used as subtitles while `<h2>` and `<h3>` are the most widely used. Here's an example:
```html
<h1>How to put an elephent into a fridge?</h1>
<!-- content -->

  <h2>Open the door</h2>
  <!-- content -->
    <h3>Make sure it's wide enough first</h3>
	<!-- content -->
	
	<h3>Push heavily!</h3>
	<!-- content -->

  <h2>Push it in</h2>
  <!-- content -->

  <h2>Close the door</h2>
  <!-- content -->
```

> The space before the `<h2>` and `<h3>` is there to help you understand their relation but they don't really exist.

Every `<h1>` and `<h2>` is underlined with a thick light-gray line just like GitHub. If you don't like it, you can add `.tex-title-no-line` class to `.textretty` container.

### Paragraph

Paragraph is defined with `<p>`. Every `<p>` tag is a paragrph. But remember two lines in one `<p>` tag is not two paragraph.

```html
<!-- I'm a paragraph -->
<p>The text in a paragraph.<p>

<!-- I'm just a paragraph but not two -->
<p>The text in line 1.<br>
The text in line 2.</p>
```

You can emphasize some important parts of a paragraph with bold and italic styles. `<strong>` and `<b>` are used for bold text while `<em>` and `<i>` are uesd for italic text. 
But attention, `<strong>` and `<em>` mean the text is really important and you're emphasizing it. `<b>` and `<i>` just make the text bold or italic and don't has certain meaings.

> Please turn to [this page](https://bigcoke233.github.io/textretty,css) for more information.

---

Copyright &copy; 2020 Eltrac Koalar, All rights reserved.
