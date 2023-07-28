---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if 1 %}
  You can also find my articles on <a href="{{https://scholar.google.com/citations?user=EwQEzCsAAAAJ&hl=en}}"> Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
