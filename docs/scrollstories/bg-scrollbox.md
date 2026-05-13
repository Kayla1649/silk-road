---
title: Background Scrollboxes
layout: scrollstory
permalink: bg-scrollbox
bg-image: /silk-road/assets/images/flowers-3.jpg
---

<div class="scrolly-section">
  <div class="sticky-thing">
    <div class="background-scroll-container">
      {% include scrollybox/bg-ss-image.html image-path="/silk-road/assets/images/image_3.jpg" position="center" %}
    </div>
  </div>
  <div class="steps">
    {% include scrollybox/step.html text="A text box can appear over a centralized background image." %}
  </div>
</div>

<div class="scrolly-section">
  <div class="sticky-thing">
    <div class="background-scroll-container">
      {% include scrollybox/bg-ss-image.html image-path="/silk-road/assets/images/hike-3.jpg" position="center" %}
    </div>
  </div>
  <div class="steps">
    {% include scrollybox/step.html text="Each panel can use its own centralized image." %}
  </div>
</div>
