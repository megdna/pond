---
layout: post
permalink: /blog
title: Blog
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

{% for post in site.posts %}
<section>
  <article>
    <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>{% if page.image %}<img src="{{ page.image | prepend: site.baseurl | prepend: site.url }}">{% endif %}</h4>
    <p>{{ post.description }}</p>
    <cite>{{ post.date | date_to_string }}</cite>
  </article>
</section>
{% endfor %}