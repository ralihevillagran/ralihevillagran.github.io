---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---
## Current course(s)

{% include base_path %}

{% for post in site.teaching reversed %}
  {% if post.type == "Undergraduate course" %}
    {% include archive-single.html %}
  {% endif %}  
{% endfor %}

## Previous Courses

| | Course | Institution |
|---|---|---|
|***Spring C term 2025*** | MA 2051 - Ordinary Differential Equations | Worcester Polytechnic Institute
|***Fall B term 2024*** | MA 2071 - Matrices and Linear Algebra I | Worcester Polytechnic Institute
|***Fall A term 2025*** | MA 1023 - Calculus III | Worcester Polytechnic Institute
|***Spring C term 2025*** | MA 1023 - Calculus III (two groups) | Worcester Polytechnic Institute
|***Fall B term 2024*** | MA 2071 - Matrices and Linear Algebra I | Worcester Polytechnic Institute
|***Fall A term 2024*** | MA 1022 - Calculus II | Worcester Polytechnic Institute
|***Spring C term 2024*** | MA 1023 - Calculus III (two groups) | Worcester Polytechnic Institute
|***Fall B term 2023*** | MA 1022 - Calculus II | Worcester Polytechnic Institute
|***Fall A term 2023*** | MA 1022 - Calculus II | Worcester Polytechnic Institute
