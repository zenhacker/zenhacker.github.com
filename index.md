---
layout: page
title: ZenHacker
tagline: 
---
{% include JB/setup %}



## Recently Post
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
    
## Common Link
### Search
* [Google](http://www.google.com)
* [百Google度](http://www.baigoogledu.com)

## Refs

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)




