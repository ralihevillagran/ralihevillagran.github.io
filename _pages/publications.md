---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile </a> and all preprint versions on <a href="https://arxiv.org/search/?query=ralihe&searchtype=all">arXiv</a>. 
  </div> 
{% endif %}

{% include base_path %}
<p style="font-size:25px;"><b>Journal publications</b></p>
{% for post in site.publications reversed %}
  {% if post.type == "Journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<p style="font-size:25px;"><b>Refereed conference</b></p>
{% for post in site.publications reversed %}
  {% if post.type == "Referred Conferences and Book Chapters" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<p style="font-size:25px;"><b>Submitted</b></p>  
{% for post in site.publications reversed %}
  {% if post.type == "Submitted" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
