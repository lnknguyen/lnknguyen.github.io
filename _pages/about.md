---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Aalto University</a>

profile:
  align: right
  image: profile_pic.jpeg
  image_circular: false # crops the image to make it circular
  

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

{Science, Data, Software} 

Call me [Nguyen](https://www.youtube.com/shorts/qCDNJUHRlaM).
<button type="button" class="tts-btn" onclick="speakText('Nguyen')">🔊</button>

<script>
  function speakText(text) {
    if (!('speechSynthesis' in window)) {
      alert('Text-to-speech is not supported in this browser.');
      return;
    }
    // stop any current speech
    window.speechSynthesis.cancel();

    const u = new SpeechSynthesisUtterance(text);
    u.lang = 'en-US';   // or 'vi-VN' if you want Vietnamese voice
    u.rate = 1.0;
    u.pitch = 1.0;

    window.speechSynthesis.speak(u);
  }
</script> I am a <Postdoctoral Researcher \|  Research Software Engineer> at Aalto University, funded by the LUMI AI Factory and affiliated with the [ELLIS Institute Finland](https://www.ellisinstitute.fi/). My work focuses on improving the computational aspects of research, with an emphasis on MLOps practices.

Earlier, I was a Doctoral Researcher at the [DigiTraces Lab](https://www.digitraceslab.com/). My research involved learning behavioral structure in large-scale digital traces and leveraging those patterns to predict mental health markers using statistical and machine learning methods. Besides that, I am interested in promoting open and reproducible science by publishing reproducible analysis pipeline and contributing to open-source code.

Before that, I earned an M.Sc. in Machine Learning, Data Science, and Artificial Intelligence (Macadamia) from Aalto University.

Even before this, I worked as an iOS software developer at [ParkMan](https://parkman.io), a startup based in Finland.
