---
layout: home
title: navigation.news
---
{%- for post in site.posts -%}

### [{{post.title}}]({{ post.url | relative_url }})
{{ post.excerpt | strip_html | truncatewords:30 }}

{%- endfor -%}