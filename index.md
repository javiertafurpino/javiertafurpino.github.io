---
layout: home
title: Welcome
---

# Welcome to My Personal Blog

Hello! I'm Javier Tafur, a passionate developer focused on creating innovative solutions. Here you'll find my thoughts, projects, and experiences in the world of technology.

## Latest Posts

{% for post in site.posts limit:3 %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Featured Projects

{% for project in site.projects limit:2 %}
### [{{ project.title }}]({{ project.url }})
{{ project.excerpt }}
{% endfor %}

[View All Projects](/projects)