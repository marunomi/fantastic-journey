---
layout: default
title: my first site
---

# maru

{% for post in site.posts %}

-[{{post.title}}]({{post.url}})

{% endfor %}
