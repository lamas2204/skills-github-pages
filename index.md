---
title: Daily Learning
permalink: /
layout: default
---

<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review

## Latest Post
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}