---
layout: default
title: Telmo Menezes
---


# Latest Posts
  
{% for post in site.posts limit:20 %}
* {{ post.date | date_to_string }}</span> &raquo; [{{ post.title }}]({{ BASE_PATH }}{{ post.url }})    
{% endfor %}