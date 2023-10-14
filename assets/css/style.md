---
layout: post
permalink: /style
title: "Style Demo"
description: This is a demonstration of the elements in CSS.
sitemap: false
---
<h3 id="nav">Navigation <a class="anchor" href="#nav">#</a></h3>

This is the main `nav` with arrows.

<nav>
<a href="#article">Article</a>
<a href="#aside">Aside</a>
<a href="#blockquote">Blockquote</a>
<a href="#code">Code</a>
<a href="#details">Details</a>
<a href="#lists">Lists</a>
<a href="#media">Media</a>
<a href="#table">Table</a>
</nav>

<h3 id="article">Article <a class="anchor" href="#article">#</a></h3>

This is an `article` showing some basic styling.

<article>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<hr>
<p><b>Bold</b></p>
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
</article>

<h3 id="aside">Aside <a class="anchor" href="#aside">#</a></h3>

This is an `aside` which floats to the right.

<aside>
<p><b>Lorem Ipsum</b></p>
<p><i>Lorem ipsum dolor sit amet, consectetur adipiscing elit</i></p>
</aside>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Here are two `aside` boxes within a `section`.

<section>
<aside>
  <h4>Project</h4>
  <img src="https://placekitten.com/200/200" alt="Photo of kitten(s)">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
  <cite>Meta</cite>
</aside>
<aside>
  <h4><a href="https://example.com" target="_blank">Post</a></h4>
  <p>Description</p>
  <cite>Date</cite>
</aside>
</section>

<h3 id="blockquote">Blockquote <a class="anchor" href="#blockquote">#</a></h3>

This is a `blockquote` with a `cite`.

> Lorem ipsum dolor sit amet
>
> <cite>Anonymous</cite>

<h3 id="code">Code Block <a class="anchor" href="#code">#</a></h3>

This can display a block of `code`.

```
body {
  background: var(--bg);
  color: var(--text);
  font-size: 1rem;
  line-height: 1.5;
  margin: 0;
}
```

Here is some pre-formatted text using `pre`.

<pre>
H   H  EEEEE  L     L      OOO     W   W   OOO   RRRR   L     DDDD   !!
H   H  E      L     L     O   O    W W W  O   O  R   R  L     D   D  !!
HHHHH  EEEEE  L     L     O   O    W W W  O   O  RRRR   L     D   D  !!
H   H  E      L     L     O   O     W W   O   O  R   R  L     D   D
H   H  EEEEE  LLLLL LLLLL  OOO      W W    OOO   R   R  LLLLL DDDD   !!
</pre>

This is a keyboard using `kbd`!

<p><kbd>control</kbd> + <kbd>C</kbd></p>
<p><kbd><kbd>control</kbd> + <kbd>V</kbd></kbd></p>

<p>
<kbd>`</kbd> <kbd>1</kbd> <kbd>2</kbd> <kbd>3</kbd> <kbd>4</kbd> <kbd>5</kbd> <kbd>6</kbd> <kbd>7</kbd> <kbd>8</kbd> <kbd>9</kbd> <kbd>0</kbd> <kbd>-</kbd> <kbd>=</kbd> <kbd>delete</kbd>
</p>
<p>
<kbd>tab</kbd> <kbd>Q</kbd> <kbd>W</kbd> <kbd>E</kbd> <kbd>R</kbd> <kbd>T</kbd> <kbd>Y</kbd> <kbd>U</kbd> <kbd>I</kbd> <kbd>O</kbd> <kbd>P</kbd> <kbd>[</kbd> <kbd>]</kbd> <kbd>\</kbd>
</p>
<p>
<kbd>caps</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> <kbd>F</kbd> <kbd>G</kbd> <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> <kbd>;</kbd> <kbd>'</kbd> <kbd>return</kbd>
</p>
<p>
<kbd>shift</kbd> <kbd>Z</kbd> <kbd>X</kbd> <kbd>C</kbd> <kbd>V</kbd> <kbd>B</kbd> <kbd>N</kbd> <kbd>M</kbd> <kbd>,</kbd> <kbd>.</kbd> <kbd>/</kbd> <kbd>shift</kbd>
</p>

<h3 id="details">Details/Summary <a class="anchor" href="#details">#</a></h3>

The `details` of this element are hidden behind a `summary`.

<details>
  <summary>Summary</summary>
  Some text
</details>

<h3 id="lists">Lists <a class="anchor" href="#lists">#</a></h3>

<p><u>Description</u></p>
<dl>
  <dt>Item</dt>
  <dd>Description</dd>
  <dt>Item</dt>
  <dd>Description</dd>
</dl> 

<p><u>Ordered</u></p>
1. Item
2. Item
    1. Item
    2. Item
        1. Item
        2. Item

<p><u>Unordered</u></p>
* Item
* Item
  * Item
  * Item
    * Item
    * Item

<h3 id="media">Media <a class="anchor" href="#media">#</a></h3>

This is an `audio` sample.

<audio controls src="{{ site.baseurl}}/assets/media/sample.mp3"></audio>

This is a `video` on loop.

<video controls loop src="{{ site.baseurl}}/assets/media/sample.mp4"></video>

This is a site inside an `iframe`.

<iframe src="https://example.com"> </iframe>

This is a pdf inside an `object`.

<object type="application/pdf" data="{{ site.baseurl}}/assets/media/sample.pdf"></object>

This is an image inside a `figure` with `figcaption`.

<figure>
  <img src="https://placekitten.com/800/800" alt="Photo of kitten(s)">
  <figcaption>Here is a caption for the photo.</figcaption>
</figure>

<h3 id="table">Table <a class="anchor" href="#table">#</a></h3>

This is a `table` with overflow contained in a `figure`.

<figure>
  <table>
    <caption>Table Title</caption>
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
  <figcaption>Table Caption</figcaption>
</figure>

ꜛ <a href="#nav">Return to Top</a>