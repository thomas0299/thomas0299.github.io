---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
My [linkedin](https://www.linkedin.com/in/thomas-s-adler/) has the most up to date and complete information for my CV. Plus they take care of the formatting.

Education
======
![image info](./images/profile.JPG)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Research
======
  <ul>{% for post in site.research %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Professional Projects
======
  <ul>{% for post in site.professional_projects %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Personal Projects
======
  <ul>{% for post in site.personal_projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
