---
layout: default
title: Archive
permalink: /archive
---
# Archive

## Comics

<ul class="post-list archive-ul">
  {% for post in site.categories.comic %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Guide to UW

Please see the [blog](/blog) page.
