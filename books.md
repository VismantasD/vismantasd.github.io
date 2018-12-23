---
layout: page
title: Books I read
permalink: /books/
---

Well this is a place t  list all my books

<ul>
  {% for post in site.posts %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
                </li>
                  {% endfor %}
  </ul>


<ul>
  {% for post in site.books %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
                </li>
                  {% endfor %}
  </ul>


