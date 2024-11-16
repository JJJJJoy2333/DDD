---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!--
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.profile {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  text-align: justify;
}

.news-container {
  position: relative;
  width: 300px;
  height: 200px;
  overflow: hidden;
  border: 1px solid #ccc;
  margin: 20px auto;
}

.news-scroll {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  height: 100%;
  overflow-y: hidden;
}

#news-list {
  list-style-type: disc;
  padding: 0;
  margin: 0;
  transition: transform 1s ease-in-out;
}

#news-list li {
  padding: 10px;
  border-bottom: 1px solid #eee;
}

#news-list li:last-child {
  border-bottom: none;
}
</style>
-->
<h1 style="color:#B22222;">Profile</h1>

<span style="font-size: 16px;">
Dandan Ding received her B. Eng. degree (Honor.) in Communication Engineering from Zhejiang University, China, in 2006. During 2007 to 2008, she was an exchange student in Microelectronic Systems Laboratory (GR-LSM) of EPFL, Switzerland. After returning to Zhejiang University, she earned her Ph.D. degree in June 2011, and served first as a postdoc researcher from July 2011 through June 2013, then as a research associate in the Multimedia Communications Laboratory (MCL) till 2015. Since 2016, she has been with the Department of Information Science and Engineering, Hangzhou Normal University as a faculty member with tenure track. Her research interests include artificial intelligence based image/video processing, video coding algorithm design and optimization, point cloud sampling and compression, and SoC design.
</span>

<span style="font-size: 16px;">
She is an active member in video coding standardization. In 2007, she was involved in the standardization activity of MPEG reconfigurable video coding and made great contribution. In 2011, she won the MPEG appreciation prize because her leadership in the MPEG activities. She has published around 50 papers and applied 20 patents in internal journals and conferences.
</span>

<span style="font-size: 16px;">
Currently, she is active in the development of new video coding algorithms for the new generation video coding standards, such as AV2. She is invited to AOM symposium in 2019 to report her research work in AV1. Since 2018, she has continuously received the research grant sponsored by Google’s Chrome University Relationship Program (CURP). She is the first author for the first AI+ compression review paper published in the leading IEEE journal – The Proceedings of the IEEE.
</span>

<h3 style="color:#B22222;">News</h3>
<div class="news-container">
  <div class="news-scroll">
    <ul id="news-list">
      <li style="font-size: 16px;"><strong>2024-07-06: </strong>The paper "Dynamic Point Cloud Geometry Compression Method Based on Time Domain Attention Mechanism" by Zhu Jiahao from our research group has been recommended to participate in the Best Paper of ChinaMM2024.</li>
      <!--
      <li>2023-09-15: Received a research grant from Google CURP.</li>
      <li>2023-08-10: Presented at the AOM symposium 2023.</li>
      <li>2023-07-01: Started a new project on point cloud compression.</li>
      <li>2023-06-15: Won the best paper award at ICIP 2023.</li>
      <li>2023-05-01: Joined the editorial board of IEEE Transactions on Image Processing.</li>
      -->
    </ul>
  </div>
</div>
<!--
<script>
document.addEventListener('DOMContentLoaded', function() {
  const newsList = document.getElementById('news-list');
  if (!newsList) {
    console.error('news-list element not found');
    return;
  }

  const items = newsList.querySelectorAll('li');
  if (items.length === 0) {
    console.error('No news items found');
    return;
  }

  const itemHeight = items[0].offsetHeight;
  let currentIndex = 0;

  function scrollNews() {
    currentIndex = (currentIndex + 1) % items.length;
    newsList.style.transform = `translateY(-${currentIndex * itemHeight}px)`;
  }

  setInterval(scrollNews, 3000); // 每3秒滚动一次
});
</script>
-->


