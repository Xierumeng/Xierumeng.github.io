---
layout: default
title: Blag
permalink: /blog
---
# Blog

Random ramblings. My current blog project is an introductory guide to the University of Waterloo.

## Guide to UW

As I am a computer engineering student, any information I have will focus on my program. However, the information is also applicable to other programs in the faculty of engineering, and perhaps useful in general with regards to UW.

***Disclaimer: Use this information at your own risk. Always check with official sources and with people who are more qualified than I am. I will not be held liable for anything that goes wrong from this website.***

### Graduation Series:

Coming soon! Topics will include fourth year, TEs, full-time offers (and negotiation), Iron Ring ceremony, convocation.

### Upper Year Series:

Coming soon! Topics will include second year, third year, CSEs, NSEs, US co-ops (if I can get any :')), extracurriculars I found enjoyable.

### Onboarding Series:

First year advice.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWOnboarding %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Acceptance Series:

After accepting and meeting the conditional offer.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWAcceptance %}
    <li class="archive-li">
      {{ post.date | date: "%Y-%m-%d" }} <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Admissions Series:

Application and admissions process.

<ul class="post-list archive-ul">
  {% for post in site.categories.blogUWAdmissions %}
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
