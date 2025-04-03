---
layout: default
---

# Welcome to My Blog

Check out my latest posts:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}