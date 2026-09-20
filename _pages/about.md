```
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

I am a **Postdoctoral Researcher and Research Software Engineer** at
[Aalto University](https://www.aalto.fi/), funded by the **LUMI AI Factory**
and affiliated with the
[ELLIS Institute Finland](https://www.ellisinstitute.fi/).

My work sits at the intersection of **machine learning, scientific computing, and research software engineering**. I help researchers design and build scalable, reproducible computational workflows, with a particular interest in **ML/HPC pipelines, GPU computing, containerized environments, workflow automation, and MLOps**.

In practice, I enjoy working on things such as deep-learning training and optimization, automated data and evaluation pipelines, HPC/Slurm workflows, Docker and Apptainer environments, experiment tracking, profiling, CI/CD, and making research software easier to reproduce and maintain.

I also occasionally teach with
[CodeRefinery](https://coderefinery.github.io/), a Nordic training network that teaches researchers practical tools for reusable, reproducible, and open research software.

I earned my **PhD in Computer Science from Aalto University in 2026**. My dissertation,
*Behavioral Sensing for Routine Characterization and Mental Health*,
studied how longitudinal data from smartphones and wearable devices can be used to characterize daily behavioral routines and their relationship with mental health.

During my PhD at the
[DigiTraces Lab](https://www.digitraceslab.com/), I worked with large-scale multimodal behavioral data spanning sleep, physical activity, mobility, communication, and device use. My research combined **statistical modeling, time-series analysis, machine learning, and reproducible cross-cohort analysis**.

Earlier, I earned an **M.Sc. in Machine Learning, Data Science, and Artificial Intelligence** from Aalto University, where my thesis focused on estimating treatment effects from clinical data using Transformer-based models.

Before moving into research, I worked as a **Senior iOS Developer** at
[ParkMan](https://parkman.io), a Finnish technology startup, where I worked on product engineering, mobile architecture, CI/CD, analytics-driven product development, and large-scale modernization of the iOS codebase.
```
