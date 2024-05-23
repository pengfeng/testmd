---
layout: default
---

<h1>Welcome to ARock</h1>

<h2> Recent Markdown Posts </h2>

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h3><a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt }}</p>
      <p><a href="{{ site.github.url }}{{ post.url }}">Read more</a></p>
    </div>
  {% endfor %}
</div>

<hr/>

<h2> HTML Pages </h2>
[HTML Pages]({{ site.github.url }}/html/test.html)

[About]({{ site.github.url }}/about)
