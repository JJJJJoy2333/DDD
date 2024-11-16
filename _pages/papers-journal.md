---
layout: archive
title: "Papers(Journal), recent 5 years"
permalink: /papers-journal/
author_profile: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.papers-journal reversed %}
  {% include archive-single.html %}
{% endfor %}


<script>
    document.addEventListener('DOMContentLoaded', function() {
      const paperItems = document.querySelectorAll('.paper-item');
      const limit = 15;

      // 隐藏超过前15个的条目
      for (let i = limit; i < paperItems.length; i++) {
        paperItems[i].classList.add('hidden-paper');
      }
    });

    function togglePapers() {
      const paperItems = document.querySelectorAll('.paper-item');
      const hiddenPapers = document.querySelectorAll('.hidden-paper');
      const showMoreBtn = document.getElementById('show-more-btn');
      const limit = 15;

      if (hiddenPapers.length > 0) {
        // 显示隐藏的条目
        hiddenPapers.forEach(paper => {
          paper.classList.remove('hidden-paper');
        });
        showMoreBtn.textContent = 'Less';
      } else {
        // 隐藏超过前15个的条目
        for (let i = limit; i < paperItems.length; i++) {
          paperItems[i].classList.add('hidden-paper');
        }
        showMoreBtn.textContent = 'More';
      }
    }
</script>
