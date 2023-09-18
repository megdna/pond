---
layout: post
permalink: /blog
title: Blog
description: This is a list of posts.
image: /images/blue.jpg
---
<h4>Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank"><code>Feed</code></a></h4>
{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
    <p class="meta"><i>{{ post.description }}</i></p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}