---
layout: home
title: Blog
permalink: /blog/
---
Here are my posts:

{% raw %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endraw %}
