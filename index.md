---
layout: page
title: "Introducing ThinkFOSS..."
category:
tags: [thinkfoss]
---
{% include JB/setup %}

[ThinkFOSS](http://thinkfoss.com) is a proud initiative of FOSS club of Amrita Vishwa Vidyapeetham, Amritapuri aka FOSS@Amrita. FOSS@Amrita from
its very beginning focused on training its members in various Open Source technologies and spreading the light of Open Source through various
national conferences like FOSSTER'09, [Debutsav](http://debutsav.in/), [conf.kde.in](https://conf.kde.in/) and many other workshops!

## What do we do?

We aim to provide you with the best Open Source training and services. We focus on three different fields especially:
<li>Open Source Solutions and applications </li>
<li>Online portal for Mentor to meet mentors, conduct workshops etc </li>
<li>Onsite training at school, college, corporate levels</li>
<br>
Come, checkout out our [website](http://thinkfoss.com) and get to know us more!


## Latest Post 
<ul class="posts">
  {% for post in site.posts limit:1 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>

## Few Posts from the past
<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt  }}
    </li>
  {% endfor %}
</ul>

