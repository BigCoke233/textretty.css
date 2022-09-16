<p align="center">
  <h1 align="center">Textretty</h1>
  <p align="center">A simple typography stylesheet.</p>
  <p align="center"><a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"></a> <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-green?style=flat-square"></a> <img src="https://img.shields.io/github/stars/BigCoke233/textretty.css?label=Star&style=flat-square"> <a href="https://github.com/BigCoke233/textretty.css/releases"><img src="https://img.shields.io/github/downloads/BigCoke233/textretty.css/total?style=flat-square"></a></p>
</p>

## Introduction

Textretty is a tiny typography css library. It can be used wherever any readable content is, such as your blog post and a document.

Additionally, textretty provide you with some simple class to construct a page container, which helps you create a single document page (just like the one you are reading) with no extra css.

## Get Started

Get the lastest version with git.

```git
$ git clone https://github.com/BigCoke233/textretty.css.git
```

Or you can just grab the `textretty.min.css` file in the main branch.

You can also get `textretty.min.css` with jsDelivr CDN, this method does not require to install.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/BigCoke233/textretty.css/dist/textretty.min.css">
```

> 说明：jsDelivr 在中国大陆地区无法访问

## Usage

Textretty only works in the element with textretty class.

```html
<head>
    <!-- ...... -->
    <link rel="stylesheet" href="textretty.css">
    <!-- ...... -->
</head>
<body>
    <!-- ...... -->
    <article class="textretty">
      <!-- your content goes here -->
    </article>
    <!-- ...... -->
</body>
```

To build a single document page as mentioned, you need `textretty-container`.

```html
<main class="textretty textretty-container">
  <header>
    <h1>Document Title</h1>
    <p>Information like publish date and category.</p>
  </header>
  <article>
    <!-- your content goes here -->
  </article>
  <footer>
    <p>Copyright &copy; 2022 Textretty</p>
  </footer>
</main>
```

If you find the container being too wide or slim, replace `textretty-container` with the ones below.

- textretty-container-slim: a slimmer page 700px wide at most.
- textretty-container-wide: a wider page 100px wide at most.

It is notable that all the containers have their `padding` defined as `2em`.