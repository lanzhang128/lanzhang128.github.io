---
layout: archive
title: "Others"
permalink: /others/
author_profile: true
---

{% include base_path %}

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single.html %}
  {% endfor %}</ul>

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
  {% endfor %}</ul>

## Blogs

<ul>{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}</ul>

## Slides

* A simple introduction about mathematical details and applications of diffusion models: [diffusion_models.pptx](https://github.com/lanzhang128/lanzhang128.github.io/blob/main/slides/diffusion_models.pptx).

* Summary of what I have done on VAEs and disentanglement before 2023: [disentanglement.pptx](https://github.com/lanzhang128/lanzhang128.github.io/blob/main/slides/disentanglement.pptx).
