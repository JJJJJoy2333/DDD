---
layout: archive
permalink: /publications/
author_profile: true
---

<h1 style="color:#B22222;">Publications, recent 5 years</h1>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
