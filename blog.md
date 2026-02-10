# Blog

Welcome to my blog. Here you’ll find posts about cloud architecture, data platforms, AI/ML, leadership, and the occasional personal project.

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
