---
layout: default
title: The Research Post
---

# The Research Post

> A blog about research !
> -- [RSS feed](https://rshpost.github.io/feed.xml)

<hr>

![research-pic](https://www.freecodecamp.org/news/content/images/size/w1000/2022/12/main-image.png)

<br>

You can find all posts ordered by date below :

### All Posts

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>
