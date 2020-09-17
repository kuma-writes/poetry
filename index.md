---
layout: page
title: Kuma's Haiku and Other Poetry
# tagline: One lens of this bear's view
description: Collecting the poetic writings of your humble bear
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="poetry/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


