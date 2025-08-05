---
layout: archive
permalink: /
title: "Yufeng's Blog"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my blog! Here you'll find my latest thoughts, projects, and discoveries.

## Recent Posts

{% include base_path %}
{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}

---

### All Posts
- [View all posts by year](/year-archive/)
- [Browse by category](/categories/)
- [Browse by tag](/tags/)
