---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Please kindly find my publications through my [Google Scholar](https://scholar.google.com/citations?user=PJbOQBMAAAAJ&hl=en) page.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
