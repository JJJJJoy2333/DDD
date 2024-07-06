---
layout: archive
title: "Papers(Journal)"
permalink: /papers_journal/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.papers_journal reversed %}
  {% include archive-single.html %}
{% endfor %}
