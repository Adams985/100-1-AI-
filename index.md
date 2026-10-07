---
layout: home
list_title: ""
---
{% for post in site.posts reversed %}
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
<p>{{ post.date | date: "%Y年%m月%d日" }}</p>
{% endfor %}
