---
layout: page
title: Borderlines
permalink: /blog/
---

Welcome to <i>Borderlines</i>, a blog where I explore how borders, law, technology, and human rights intersect to shape our world.

For posts from 2025 onwards, you may also find <a href="https://borderlinesblog.substack.com/"><i>Borderlines</i> on Substack</a> with an option to subscribe to email updates. The blog posts in Polish are distributed separately through <a href="https://pogranicza.substack.com/"><i>Pogranicza</i></a>.

<iframe src="https://borderlinesblog.substack.com/embed" width="100%" height="120" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe>

<br>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
