---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find a complete list of my publications on my Google Scholar [profile](<https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=wgny0S8AAAAJ>)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
