---
permalink: /
title: "Profile"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Dandan Ding received her B. Eng. degree (Honor.) in Communication Engineering from Zhejiang University, China, in 2006. During 2007 to 2008, she was an exchange student in Microelectronic Systems Laboratory (GR-LSM) of EPFL, Switzerland. After returning to Zhejiang University, she earned her Ph.D. degree in June 2011, and served first as a postdoc researcher from July 2011 through June 2013, then as a research associate in the Multimedia Communications Laboratory (MCL) till 2015. Since 2016, she has been with the Department of Information Science and Engineering, Hangzhou Normal University as a faculty member with tenure track. Her research interests include artificial intelligence based image/video processing, video coding algorithm design and optimization, point cloud sampling and compression, and SoC design.

She is an active member in video coding standardization. In 2007, she was involved in the standardization activity of MPEG reconfigurable video coding and made great contribution. In 2011, she won the MPEG appreciation prize because her leadership in the MPEG activities. She has published around 50 papers and applied 20 patents in internal journals and conferences.

Currently, she is active in the development of new video coding algorithms for the new generation video coding standards, such as AV2. She is invited to AOM symposium in 2019 to report her research work in AV1. Since 2018, she has continuously received the research grant sponsored by Google’s Chrome University Relationship Program (CURP). She is the first author for the first AI+ compression review paper published in the leading IEEE journal – The Proceedings of the IEEE.


News
======
{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
