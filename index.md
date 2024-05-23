---
layout: default
---

<h1>Welcome to ARock</h1>

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <p><a href="{{ post.url }}">Read more</a></p>
    </div>
  {% endfor %}
</div>

[About](/about/)
