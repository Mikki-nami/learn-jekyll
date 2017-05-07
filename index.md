---
layout: page
title: Home
---

# Hello Elves! (This is word!)

This are the contents of the Jekyll front page.


Stranka ve výstavbe

<p>
                <img src="stranky_ve _vystavbe.jpg" alt="stranky_ve _vystavbe" width="500" height="300">
          </p>


See the posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Pages

And even normal pages:

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
