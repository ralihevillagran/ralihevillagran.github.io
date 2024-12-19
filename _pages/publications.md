---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile </a> and all preprint versions on <a href="https://arxiv.org/search/?query=ralihe&searchtype=all">arXiv</a>.
  <p>(*)Refereed conference</p>
  <p>(**)Submitted</p>   
  </div> 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.type == "type" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
