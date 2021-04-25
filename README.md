# Introduction
Welcome to the CSCI3251 Project of Team M.
In this repository we are tasked to:
- [x] Start some issues.
- [x] Setup the project board.
- [x] Setup the readme file
- [ ] Updating our GitHub Pages.
- [ ] Label everything properly.
- [ ] Write C code and use GitHub Actions to run it automatically.
- [ ] Get a status badge.
- [ ] Promote our repository.


**Please read `tasks.md` to start your work.**
 

# Code

# Contributors
{% for stu in site.stu %}
  <h2>{{ stu.image }} - {{ stu.user }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

