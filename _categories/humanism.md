---
title: Category - Humanism
tag: humanism
layout: page
permalink: "/category/humanism"
hero_height: is-small
hero_darken: true
menubar: categories_leftbar
show_sidebar: false
---

<h2>Posts</h2>

{% for post in site.categories.humanism %}
<ul style="padding-left:30px"> 
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endfor %}