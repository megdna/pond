---
layout: post
permalink: /blog
title: Blog
image: /images/blue.jpg
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

{% for post in site.posts %}
<article>
  <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a></h4>
  <p><i>{{ post.description }}</i></p>
  <p class="meta">{{ post.date | date_to_string }}</p>
</article>
{% endfor %}