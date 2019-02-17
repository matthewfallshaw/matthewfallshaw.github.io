---
last_modified_at: 2019-02-17
---
{% for post in site.posts %}
* {{ post.date | date: "%Y-%m-%d" }} \| [{{ post.title }}]({{ post.url }})
{% endfor %}
