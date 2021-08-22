---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{author.googlescholar}">my Google Scholar profile</a>.</u>
{% endif %}

{% comment %}
You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=BRw9kdoAAAAJ">my Google Scholar profile</a>.</u>
{% endcomment %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
