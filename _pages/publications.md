---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on [<u><a>my Google Scholar profile</a>.</u>](<https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=wgny0S8AAAAJ>)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
