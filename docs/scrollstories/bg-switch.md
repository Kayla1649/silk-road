---
title: Background Switch
layout: scrollstory
permalink: bg-switch
bg-image: /silk-road/assets/images/fish-1.jpg
---

{% include scrollybox/bg-switch.html
  before="/silk-road/assets/images/fish-1.jpg"
  after="/silk-road/assets/images/fish-2.jpg"
  height="100vh"
%}

<div class="scrolly-section">
  <div class="sticky-thing">
    {% include scrollybox/bg.html image-path="/silk-road/assets/images/fish-4.jpg" %}
  </div>
  <div class="steps">
    {% include scrollybox/step.html text="This scrollbox uses a centralized background image." %}
  </div>
</div>
