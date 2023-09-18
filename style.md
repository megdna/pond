---
layout: post
permalink: /style
title: "Style Demo"
description: This is a demonstration of the elements in CSS.
image: /images/blue.jpg
---
### Article

This is an `article` showing some basic styling inside. All the typography uses `rem` for sizing. This means that accessibility is maintained for those who change their browser font size.

<article>
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
<hr>
**Lists:**

* Item
* Item
  * Item
  * Item
    * Item
    * Item

1. Item 1
2. Item 2
    a. Item a
    b. Item b
        i. Item i
        ii. Item ii

<hr>
**Styles:**

*Italic*

<small>Small</small>

<s>Strikethrough</s>

Subscript: H<sub>2</sub>O

Superscript<sup>1</sup>

<u>Underlined</u>

[URL](https://example.com)

<abbr title="Uniform Resource Locator">URL</abbr> Abbreviated

<mark>Highlighted</mark>

<mark>Highlighted [URL](https://example.com)</mark>

Keyboard: <kbd>Cmd</kbd>
</article>


### Aside

This is an `aside` which floats to the right.

<aside>
**Title**

Text
</aside>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


### Blockquote

This is a `blockquote` with a `cite`.

> Lorem ipsum dolor sit amet
>
> <cite>Anonymous</cite>


### Code Block

This can display a block of `code` using `pre`.

```
body {
  color: var(--text);
  background: var(--bg);
  font-size: 1.15rem;
  line-height: 1.5;
  margin: 0;
}
```

<pre>Some pre-formatted text</pre>


### Details/Summary

The `details` of this element are hidden behind a `summary`.

<details>
  <summary>Summary</summary>
  Some text
</details>


### Media

This is an image inside a `figure` with `figcaption`.

<figure>
  <img src="https://placekitten.com/800/800" alt="Photo of kittens">
  <figcaption>Here is a caption for the photo.</figcaption>
</figure>


### Section

This is a `section` with some text.

<section>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</section>

### Table

<table>
  <caption>Table Caption</caption>
	<thead>
	  <tr>
		  <th>Table Heading 1</th>
			<th>Table Heading 2</th>
			<th>Table Heading 3</th>
			<th>Table Heading 4</th>
			<th>Table Heading 5</th>
		</tr>
	</thead>
	<tbody>
	  <tr>
		  <td>Table Cell 1</td>
			<td>Table Cell 2</td>
			<td>Table Cell 3</td>
			<td>Table Cell 4</td>
			<td>Table Cell 5</td>
		</tr>
	  <tr>
		  <td>Table Cell 1</td>
			<td>Table Cell 2</td>
			<td>Table Cell 3</td>
			<td>Table Cell 4</td>
			<td>Table Cell 5</td>
		</tr>
	  <tr>
		  <td>Table Cell 1</td>
			<td>Table Cell 2</td>
			<td>Table Cell 3</td>
			<td>Table Cell 4</td>
			<td>Table Cell 5</td>
		</tr>
	  <tr>
		  <td>Table Cell 1</td>
			<td>Table Cell 2</td>
			<td>Table Cell 3</td>
			<td>Table Cell 4</td>
			<td>Table Cell 5</td>
		</tr>
	</tbody>
</table>