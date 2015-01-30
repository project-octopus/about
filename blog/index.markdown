---
layout: page
title: Project Octopus Blog
---

<div class="posts">
{% for post in site.posts %}
<article class="post">
<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
<div class="entry">
<small>{{ post.date | date_to_long_string }}</small> {{ post.content | strip_html | truncatewords:40}}
<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
</div>
</article>
{% endfor %}
</div>
