---
layout: post
permalink: /blog
title: Blog
image: /images/blue.jpg
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

{% for post in site.posts %}
<article>
  <div class="blog-item">
    <a class="post-link" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
    <p><i>{{ post.description }}</i></p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
</article>
{% endfor %}