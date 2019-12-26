---
layout: default
title: Archive
permalink: /archive
---
# Archive

<ul class="post-list archive-ul">
  {% for post in site.categories.page %}
    <li class="archive-li">
      {{ post.date }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
