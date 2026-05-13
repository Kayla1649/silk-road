---
title: Header Examples
layout: xanthan
date: 2024-10-24
header-image: /silk-road/assets/images/pano-1.jpg
---

# Image Header Examples

Use centralized image paths for page headers and section headers:

```yaml
header-image: /silk-road/assets/images/pano-1.jpg
```

For image-based includes, use the same absolute deployed path:

```liquid
{% include images/jumbotron.html
  height="30vh"
  image-path="/silk-road/assets/images/pano-1.jpg"
  title="Section Heading"
%}
```

{% include images/jumbotron.html
  height="30vh"
  image-path="/silk-road/assets/images/pano-1.jpg"
  title="Section Heading"
%}

```liquid
{% include scrollybox/bg.html
  height="40vh"
  image-path="/silk-road/assets/images/pano-1.jpg"
%}
```

{% include scrollybox/bg.html
  height="40vh"
  image-path="/silk-road/assets/images/pano-1.jpg"
%}
