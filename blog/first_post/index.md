---
title: First Post
date: 2026-9-19
description: This is experiment. This is my first post.
categories: ['filter3']
draft: false # Change to true to not render the post in on the website
---

This is experiment


## Title

---
Am I doing right?


## Markdown Code Snippets

<br>

```
`this is code snippets`
```

<br>

They result in unformated, monospace text:

<br>

`this is code snippets`

## Markdown Basics

`*italics*` = *italics*

`**bold**` = **bold**

`[linktext](example.com)` = [linktext](example.com)

## More Markdwon Basics

<br>

`# top level header`

<h1>top level header</h1>

<br>

`## lower level header`

<h2>lower level header<h2>

## Useful HTML in Markdown

`<br>` = line break

<br>

```{.html}
<details><summary>summary text</summary>

collapsable content

</details>
```

<br>

<details><summary>summary text</summary>collapsable content</details>


## Code Blocks

It's possible to do code blocks with langauge highlighting.

This:

```{.default}
\`\`\`{.python}
print("hellow world!")

def testfunction(input):
    print("Hi!")
\`\`\`
```

Results in:

```{.python}
print("hellow world!")

def testfunction(input):
    print("Hi!")
```

Many, many languages are supported and can be highlighted.

Images:

`![alt text](https://quarto.org/quarto.png)`


![alt text](https://quarto.org/quarto.png)

Of course, this is an external image. You an also store images in the repository, and then refer to them by the relative file path. Something like:

`![](../image.png)`

Where `..` goes up one directory, and then you can refer to files by their file path.


More information about markdown: <https://quarto.org/docs/authoring/markdown-basics.html>