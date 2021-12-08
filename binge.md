---
layout: default
mathjax: true
---

Binge-Reading is a project to spend several months reading a collection of books in mathematics. The idea is inspired by Covid-19.

## A Comprehensive Course in Analysis, by Simon ##

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Methods of Modern Mathematical Physics, by Simon-Reed ##

### Acknowledgements ###

The template is adapted from the [tufte-css](https://edwardtufte.github.io/tufte-css/) project.