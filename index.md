---
layout: page
title: Home
---

# Hello Elves! (This is word!)

This are the contents of the Jekyll front page.


Stranka ve výstavbe

<body>
    <div class="gallery">
          <a target="_blank" href=stranky_ve _vystavbe.jpg">
                <img src="stranky_ve _vystavbe.jpg" alt="stranky_ve _vystavbe" width="500" height="300">
           </a>
        </div>
      </body>


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
