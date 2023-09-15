---
layout: page
permalink: /blog
title: Blog
description: This is a list of posts.
image: /assets/images/dog.jpg
---
<a class="button" href="{{ site.baseurl }}/feed.xml" target="_blank">Subscribe to feed</a>

{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
    <p class="meta"><i>{{ post.description }}</i></p>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}