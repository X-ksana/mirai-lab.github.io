---
layout: page
title: Journal Club
description: Bi-weekly paper discussions
---

{% include schedule.html %}

## Archive
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %Y" }})
{% endfor %}