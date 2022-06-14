---
layout: single
title: Pictures
permalink: /images/
---

{% for image in site.data.album %}
  <figure>
    <a href="/assets/images/{{ image }}">
      <img src="/assets/images/{{ image }}" />
    </a>
    <figcaption>CAPTION</figcaption>
  </figure>
{% endfor %}