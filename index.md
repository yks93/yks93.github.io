---
layout: default
title: Home
---

I work on machine learning, geometry, and systems.

My focus is on understanding how representations emerge, how structure is encoded, and how models generalize.

---

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
