---
layout: about
title: about
permalink: /
subtitle: Research Software Engineer · Aalto University

profile:
  align: right
  image: profile_pic.jpeg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

### {Science, Data, Software}

Call me [Nguyen](https://www.youtube.com/shorts/qCDNJUHRlaM).
<button type="button" class="tts-btn" onclick="speakText('Nguyen')">🔊</button>

<script>
  function speakText(text) {
    if (!('speechSynthesis' in window)) {
      alert('Text-to-speech is not supported in this browser.');
      return;
    }

    window.speechSynthesis.cancel();

    const u = new SpeechSynthesisUtterance(text);
    u.lang = 'en-US';
    u.rate = 1.0;
    u.pitch = 1.0;

    window.speechSynthesis.speak(u);
  }
</script>

I am a [Research Software Engineer](https://ukrse.github.io/who.html) at [Aalto University](https://www.aalto.fi/), funded by the LUMI AI Factory and affiliated with the [ELLIS Institute Finland](https://www.ellisinstitute.fi/).

My work sits at the intersection of machine learning, scientific computing, and research software engineering. I help researchers design and build scalable, reproducible computational workflows, with a particular interest in **MLOps**.

In practice, I enjoy working with deep learning training and optimization, automated data and evaluation pipelines, HPC/Slurm workflows, Docker and Apptainer environments, experiment tracking, profiling, CI/CD, and in general, making research software easier to reproduce and maintain. I also occasionally teach in [CodeRefinery](https://coderefinery.github.io/), a Nordic training network that teaches researchers practical tools for reusable, reproducible, and open research software.

I earned my PhD in Computer Science from Aalto University in 2026, under the supervision of [Dr. Talayeh Aledavood](https://talayeh.xyz/) at the [DigiTraces Lab](https://www.digitraceslab.com/). My [dissertation](https://aaltodoc.aalto.fi/items/d0cd3534-4e5f-4ea3-8fb9-e11e0fa6953f) studies how longitudinal data from smartphones and wearable devices can be used to characterize daily routines and study mental health.

Before moving into research, I worked as a **Senior iOS Developer** at [ParkMan](https://parkman.io), a Finnish parking management platform. There, I worked on product engineering, product roadmap, mobile architecture, CI/CD platform, and large-scale modernization of the iOS codebase.

