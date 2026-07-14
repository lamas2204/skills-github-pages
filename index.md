---
title: Daily Learning
#permalink: /
layout: default
---

<img alt="Machine Learning" src="_resources/MchnLrnng.png" width="100" align="left" >
<br/>
<br/>
<br/>
<br/>

## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review
The background color is `#ffffff` for light mode and `#000000` for dark mode.

## Latest Post
{% for post in site.posts %}
- [{{ post.title }} - {{ post.date | date: "%Y-%m-%d" }}]({{ post.url | absolute_url }})
{% endfor %}