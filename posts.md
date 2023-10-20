---
layout: post
permalink: /posts
title: Posts
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

<section>
{% for post in site.posts %}
<aside>
  <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>{% if post.image %}<img alt="{{ post:alt }}" src="{{ post.image | prepend: site.baseurl | prepend: site.url }}">{% endif %}</h4>
  <p>{{ post.description }}</p>
  <cite>{{post.date | date: '%B %d, %Y'}} - {% capture words %}{{ post.content | number_of_words }}{% endcapture %}{% unless words contains "-" %}{{ words | plus: 250 | divided_by: 250 | append: " minute read" }}{% endunless %}</cite>
</aside>
{% endfor %}
</section>