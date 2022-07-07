---
layout: single
title: Pictures
permalink: /images/
---
{% for image in site.data.album %}
  <div style="float: left; width: 40%; margin: 2%; clear: none; position: relative">
    <figure>
      <a href="/assets/images/{{ image.image }}">
        <img src="/assets/images/{{ image.image }}" />
      </a>
      <figcaption>{{ image.caption }}</figcaption>
    </figure>
  </div>
{% endfor %}