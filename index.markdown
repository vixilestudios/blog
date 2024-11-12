---
layout: home
title: "Home"
---

<h2 class="post-list-heading">Recent Posts</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li class="post-item">
      <a class="post-link" href="{{ post.url }}">
        <img class="post-image" src="{{ site.url }}/assets/images/blog{{ post.image }}">
        <p class="post-text">{{ post.title }}</p>
        <p class="post-excerpt">{{ post.excerpt }}</p>
      </a>
    </li>
  {% endfor %}
</ul>
