---
layout: page
title: Projects
permalink: /projects/
---

# Projects

Here are some of the projects I've worked on:

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})

{{ project.excerpt }}

[Read more]({{ project.url }})

---
{% endfor %}