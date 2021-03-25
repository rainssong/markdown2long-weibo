# markdown-css-smartisan

> 一个基于锤子便签的markdown主题。

[<img src="https://nihaojob.github.io/markdown-css-smartisan/demo.png" width="500">](https://nihaojob.github.io/markdown-css-smartisan)

## [Demo](https://nihaojob.github.io/markdown-css-smartisan)

[预览](https://nihaojob.github.io/markdown-css-smartisan)我们的主题，你可以和[锤子便签](https://yun.smartisan.com/apps/note/md.html)对比一下。

## Install

Download [manually](https://github.com/nihaojob/https://nihaojob.github.io/markdown-css-smartisan/blob/main/github-markdown.css), from [CDNJS](https://cdn.jsdelivr.net/npm/markdown-css-smartisan/github-markdown.css), or with npm:

```
<!-- Using npm:  -->
$ npm install markdown-css-smartisan
<!-- Using yarn:  -->
$ yarn add markdown-css-smartisan
```

## Usage



```
import 'markdown-css-smartisan'
```
Import the `github-markdown.css` file and add a `markdown-body` class to the container of your rendered Markdown and set a width for it.

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="github-markdown.css">
<style>
  .markdown-body {
    box-sizing: border-box;
    min-width: 200px;
    max-width: 980px;
    margin: 0 auto;
    padding: 45px;
  }

  @media (max-width: 767px) {
    .markdown-body {
      padding: 15px;
    }
  }
</style>
<article class="markdown-body">
	<h1>Unicorns</h1>
	<p>All the things</p>
</article>
```

If you want code syntax highlighted, use GitHub Flavored Markdown rendered from [GitHub's `/markdown` API](https://docs.github.com/en/free-pro-team@latest/rest/reference/markdown).

## How

See [`generate-github-markdown-css`](https://github.com/sindresorhus/generate-github-markdown-css) for how it's generated and ability to generate your own.

<!-- ## Dev

Run `npm run make` to update the CSS. -->
