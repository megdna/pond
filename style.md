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
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<hr>
<p><b>Ordered List:</b></p>
<ol type="1">
  <li>List Item 1</li>
  <li>List Item 2
    <ol type="A">
      <li>List Item 1</li>
      <li>List Item 2</li>
    </ol>
        <ol type="a">
          <li>List Item 1</li>
          <li>List Item 2</li>
        </ol>
            <ol type="I">
              <li>List Item 1</li>
              <li>List Item 2</li>
            </ol>
                <ol type="i">
                  <li>List Item 1</li>
                  <li>List Item 2</li>
                </ol>
<p><b>Unordered List:</b></p>
<ul>
  <li>List Item 1</li>
  <li>List Item 2</li>
</ul>
    <ul>
      <li>List Item 1</li>
      <li>List Item 2</li>
    </ul>
        <ul>
          <li>List Item 1</li>
          <li>List Item 2</li>
        </ul>
            <ul>
              <li>List Item 1</li>
              <li>List Item 2</li>
            </ul>
                <ul>
                  <li>List Item 1</li>
                  <li>List Item 2</li>
                </ul>
<hr>
<p><b>Styles:</b></p>
<p></p>
<p><i>Italic</i></p>
<p><small>Small</small></p>
<p><s>Strikethrough</s></p>
<p>Subscript: H<sub>2</sub>O</p>
<p>Superscript<sup>1</sup></p>
<p><u>Underlined</u></p>
<p><a href="https://example.com" target="_blank">URL</a></p>
<p><abbr title="Uniform Resource Locator">URL</abbr> Abbreviated</p>
<p><mark>Highlighted</mark></p>
<p><mark>Highlighted <a href="https://example.com" target="_blank">URL</a></mark></p>
<p>Keyboard: <kbd>Cmd</kbd></p>
</article>


### Aside

This is an `aside` which floats to the right.

<aside>
<p><b>Lorem Ipsum</b></p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
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
  <caption>Table Caption</caption>
</table>