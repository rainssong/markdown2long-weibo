# github-markdown-css-smartisan

> 我很喜欢锤子便签的样式，于是把他们的样式抄了下来。

[<img src="https://nihaojob.github.io/github-markdown-css-smartisan/demo.png" width="500">](https://nihaojob.github.io/github-markdown-css-smartisan)

## [Demo](https://nihaojob.github.io/github-markdown-css-smartisan)

你可以从这里和官网对比一下
[官方地址](https://yun.smartisan.com/apps/note/md.html)。

## Install

暂时没有提供npm包，你可以拷贝把文件拷贝下来使用。

<!-- Download [manually](https://raw.githubusercontent.com/sindresorhus/github-markdown-css/gh-pages/github-markdown.css), from [CDNJS](https://cdnjs.com/libraries/github-markdown-css), or with npm:

```
$ npm install github-markdown-css
``` -->

## Usage

Import the `github-markdown.css` file and add a `markdown-body` class to the container of your rendered Markdown and set a width for it. GitHub uses `980px` width and `45px` padding, and `15px` padding for mobile.

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

## Dev

Run `npm run make` to update the CSS.
