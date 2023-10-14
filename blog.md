---
layout: post
permalink: /blog
title: Blog
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

<section>
{% for post in site.posts %}
<aside>
  <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>{% if page.image %}<img src="{{ page.image }}">{% endif %}</h4>
  <p>{{ post.description }}</p>
  <cite>{{ post.date | date_to_string }}</cite>
</aside>
{% endfor %}
</section>