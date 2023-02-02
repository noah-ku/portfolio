---
title: "**Hi, I'm Noah!**"
layout: custom_splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/background_orange_bordered.png

[//]: # (  actions:)

[//]: # (    - label: "Download")

[//]: # (      url: "https://github.com/mmistakes/minimal-mistakes/")
excerpt: "**I am a student at the University of California, Berkeley studying computer science.<br><br> All my school and personal projects are listed below.**"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/mc-spicy.jpeg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/mc-spicy.jpeg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "https://github.com/mmistakes/minimal-mistakes/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/mc-spicy.jpeg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/epicure_background.png
    alt: "placeholder image 2"
    title: "Epicure"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "https://github.com/mmistakes/minimal-mistakes/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/mc-spicy.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "https://github.com/mmistakes/minimal-mistakes/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/mc-spicy.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "https://github.com/mmistakes/minimal-mistakes/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

[//]: # ({% include feature_row id="intro" type="center" %})

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
