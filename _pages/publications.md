---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
$\spadesuit$ If I ever **by chance** or **by choice** discover something worth sharing with the science community, I will let you know right from here...


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
