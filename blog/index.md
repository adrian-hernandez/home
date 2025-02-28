---
layout: default
title: Blog
---
# Latest Posts

{% for post in site.posts %}
  <article class="post-preview">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date_to_string }}</time>
    {{ post.excerpt }}
  </article>
{% endfor %} 