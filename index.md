---
layout: default
title: Home
---

# Al-Istibanah – Latest Articles

{% for post in site.posts limit: 5 %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}  

{{ post.excerpt }}

[Read more →]({{ post.url }})

---

{% endfor %}
