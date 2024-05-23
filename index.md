---
layout: default
---

<h1>Welcome to ARock</h1>

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h2><a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <p><a href="{{ site.github.url }}{{ post.url }}">Read more</a></p>
    </div>
  {% endfor %}
</div>

[HTML Pages]({{ site.github.url }}/html/test.html)

[About]({{ site.github.url }}/about)
