---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  <p style="text-decoration:none;">For a full list of publications, please visit my <a href="{{ author.googlescholar }}">Google Scholar profile</a>.</p>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
