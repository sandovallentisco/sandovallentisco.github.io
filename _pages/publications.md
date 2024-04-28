---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Under construction!

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a full list of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

 
## Some selected papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Test

