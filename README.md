# Introduction
Welcome to the CSCI3251 Project of Team M.
In this repository we are tasked to:
- [x] Start some issues.
- [x] Setup the project board.
- [x] Setup the readme file
- [x] Updating our GitHub Pages.
- [x] Label everything properly.
- [x] Write C code and use GitHub Actions to run it automatically.
- [x] Get a status badge.
- [x] Promote our repository.


 

# Code

```C
{% include_relative project-team-m/code.c %}
```
![example workflow](https://github.com/csci3251-2021/project-team-m/actions/workflows/c-ccp.yml/badge.svg)

# Contributors
{% for stu in site.stu %}
- <img src="{{ stu.image }}" width="50" height="50" /><a href="https://github.com/{{ stu.user }}">@{{ stu.user }}</a> ({{ stu.name }})
  - {{ stu.content | markdownify }}
{% endfor %}

---
Last updated: {{ site.time }}
