---
layout: default
title: LineageOS builds by Razuuu
---

# Supported devices

## Exynos7885 devices is now at <a href="https://lineage.a2l5e0x1.at">https://lineage.a2l5e0x1.at</a>

{% assign sorted_pages = site.pages | sort: 'title' %}

{% for page in sorted_pages %}
{% if page.title and page.url and page.url contains "/devices/" %}
- [{{ page.title }} ({{ page.codename }})]({{ page.url | relative_url }})
{% endif %}
{% endfor %}
