---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mathematics, Department of Mathematics, Center for Research and Advanced Studies of the National Polytechnic Intitute (CINVESTAV-IPN), 2021
  * [Advisors and Thesis Title on the Mathematics Genealogy Project](https://www.mathgenealogy.org/id.php?id=278914)
    
* M.S. in Mathematics, Department of Mathematics, Center for Research and Advanced Studies of the National Polytechnic Intitute (CINVESTAV-IPN), 2017.
* B.S. in Mathematics, Faculty of Physics and Mathematics, Autonomous University of Sinaloa, Mexico, 2014

Publications
======
 [//]: <ul>{% for post in site.publications reversed %}
 [//]:  {% include archive-single-cv.html %}
 [//]: {% endfor %}</ul>

  {% include base_path %}
<p style="font-size:20px;"><b>Journal publications</b></p>
<ul>{% for post in site.publications reversed %}
  {% if post.type == "Journal" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

<p style="font-size:20px;"><b>Refereed conference</b></p>
<ul>{% for post in site.publications reversed %}
  {% if post.type == "Referred Conferences and Book Chapters" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

<p style="font-size:20px;"><b>Submitted</b></p>  
<ul>{% for post in site.publications reversed %}
  {% if post.type == "Submitted" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

[//]: # (Service and leadership)
[//]: #======
[//]: # (*Currently signed in to 43 different slack teams)

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  *[Previous Courses](https://ralihevillagran.github.io/teaching/)
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Work experience
======
* Postdoctotal Scholar, August 2023 - current position
  * Mathematical Sciences Department, Worcester Polytechnic Institute (WPI)
* Research Mentor: Bill Martin
* Postdoctoral Researcher, June 2022 -May 2023
  * Department of Mathematics and Computer Science, Eindhoven University of Technology (TU/e)
  * Mentor: Aida Abiad
