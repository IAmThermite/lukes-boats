---
layout: splash
title: Luke's Sailing Logbooks
permalink: /
header:
  overlay_image: /assets/images/header.jpg
tagline: My sailing journals and other bits and pieces that interest me about boats and stuff
---

# Logbook

Welcome! Look around! Maybe you'll find something that you enjoyed or learn something you didn't know.

## What is this for?

This is mainly a journal for my sailing adventures/races/whatever boat thing I do.
I'll do some analysis on my racing, post setup changes, and whatever else takes my fancy.
I'll write down some random notes and take photos of some things. Just something for me to have a bit of fun with.

## Why does this exist?

Basically I wanted a way I could track my progress with sailing, do some analysis on races, and other bits and pieces like tips and
tricks I've heard or discoveries I make with my sailing.
I hope to be able to look back on it and see what I've learnt and learn heaps of things from the process.

## Current and upcoming things

I recently purchaced PT862 Mr Jinks so am getting that boat set up and intend to race it in the upcoming EBYMBC races.
The first race is mid June so I'm getting everything set up for that and will break down every race and post them all here.
I sail other boats too, might have pictures of the naval whaler or if I haven't sold my Farr 3.7 then some of that too.
If I'm feeling like it I'll also post my Firebug races when I have them.

<hr />

# Latest posts

<!-- https://github.com/mmistakes/minimal-mistakes/blob/master/_layouts/home.html -->
{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>
