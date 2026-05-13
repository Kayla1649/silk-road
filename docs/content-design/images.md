---
title: Image Examples
layout: xanthan
header-image: /silk-road/assets/images/lake-1.jpg
header-height: 60vh
---

# Using Images

All image examples now use centralized deployed paths in `assets/images`.

## Inline Images

{% include images/figure.html
  class="right"
  width="40%"
  caption="What a nice view"
  alt-text="Color photograph showing a hiking trail."
  image-path="/silk-road/assets/images/hike-1.jpg"
%}

```liquid
{% include images/figure.html
  class="right"
  width="40%"
  caption="What a nice view"
  alt-text="Color photograph showing a hiking trail."
  image-path="/silk-road/assets/images/hike-1.jpg"
%}
```

## Side By Side

{% include images/figure.html class="left" width="48%" image-path="/silk-road/assets/images/dunhuang-dancers.jpg" caption="Here's an image on the left." %}
{% include images/figure.html class="left" width="48%" image-path="/silk-road/assets/images/tang-dancer.png" caption="Here's an image on the right." %}

<p style="clear:both"></p>

## Jumbotron

{% include images/jumbotron.html
  height="50vh"
  image-path="/silk-road/assets/images/dunhuang-dancers.jpg"
  title=""
%}

## Juxtapose

{% include images/juxtapose.html
  image1="/silk-road/assets/images/ota-gate-khiva2.jpg"
  image2="/silk-road/assets/images/han-coin-greek-inscription.jpg"
  caption="These sliders are most effective when images line up closely."
%}

## Carousel

{% assign images = "/silk-road/assets/images/dunhuang-dancers.png,/silk-road/assets/images/tang-dancer.png,/silk-road/assets/images/ota-gate-khiva2.jpg" | split: ',' %}
{% assign headers = "Dunhuang,Tang Dancer,Khiva" | split: ',' %}
{% assign captions = "Dunhuang dancers|Tang dancer figurine|Ota Darvoza gate" | split: '|' %}

{% include images/carousel.html
  width="80%"
  class="center"
  images=images
  headers=headers
  captions=captions
%}
