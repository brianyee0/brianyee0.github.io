---
id: 364
title: Posts
date: '2013-02-05T12:04:00-05:00'
author: brianyee0
layout: page
guid: 'http://www.brianyee.org/?page_id=364'
---


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
