---
layout: default
title: Blag
permalink: /blog
---
# Blog

Ramblings of a madman. My current blog project is an introductory guide to the University of Waterloo.

## Guide to UW

As I am a computer engineering student, any information I have will focus on my program. However, the information is also applicable to other programs in the faculty of engineering, and perhaps useful in general with regards to UW.

**Disclaimer: Use this information at your own risk. Always check with official sources and with people who are more qualified than I am. There is no trust, only verify.**

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUW %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Resources

Miscellaneous information and guides.

<ul class="post-list archive-ul">
  {% for post in site.categories.guide %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
