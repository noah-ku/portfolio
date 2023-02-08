---
title: "**Hi, I'm Noah!**"
layout: custom_splash
date: 2016-03-23T11:48:41-04:00
header:
    overlay_color: "#000"
    overlay_filter: "0.0"
    overlay_image: /assets/images/background_orange_bordered.png
excerpt: "**I am a student at the University of California, Berkeley studying computer science.<br><br> All my school and personal projects are listed below.**<br><br>"
intro:
- excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
    - image_path: /assets/images/pacman.png
      alt: "pacman"
      title: "Pacman AI"
      excerpt: "Project for CS 188<br><br>Designed different pathfinding algorithms to help Pacman find the closest dots on any random maze. Some implemented algorithms include Breadth-First Search, Depth-First Search, and A* Search."
    - image_path: /assets/images/ataxx-icon.jpeg
      alt: "ataxx"
      title: "Ataxx AI"
      excerpt: "Project for CS 61B<br><br>Created an AI that can find the best moves in the 1990 game Ataxx. The bot uses minimax and alpha-beta pruning algorithms to find the best possible move within a given depth."
    - image_path: /assets/images/ants-icon.png
      title: "Ants vs. Bees"
      excerpt: "Project for CS 61A<br><br>Developed a game based off of Plants vs. Zombies where a player must place ants on the board to prevent the bee invasion. This game uses Object-Oriented Programming to configure ant types and is written in Python."
epicure:
    - image_path: /assets/images/epicure_background.png
      alt: "epicure"
      title: "Epicure"
      excerpt: 'Epicure is a cooking simulator where players must complete fast-food orders within a certain time to earn more money. The game offers both a single-player and a multiplayer (2v2) mode. This project is published on Steam and was made with Unity and C#.'
      url: "https://noah-ku.github.io/portfolio/epicure/"
      btn_label: "Read More"
      btn_class: "btn--primary"
tjc-notify:
    - image_path: /assets/images/tjc_notify_mockup2.png
      alt: "tjc-notify"
      title: "True Jesus Church Notify"
      excerpt: 'TJC Notify is an iOS app that displays a live schedule and supports realtime updates. Push notifications are sent to users who are assigned specific duties. The app uses JavaScript and Firebase to run its database and authentication systems.'
      url: "https://github.com/mmistakes/minimal-mistakes/"
      btn_label: "Read More"
      btn_class: "btn--primary"
verse-rush:
    - image_path: /assets/images/verse-rush.png
      alt: "verse-rush"
      title: "Verse Rush"
      excerpt: 'Verse Rush is a game where any Bible verse used as input will have randomly generated blanks. Players must type in the correct word to keep progressing until all blanks are filled. This game was developed in C#.'
      url: "https://github.com/mmistakes/minimal-mistakes/"
      btn_label: "Read More"
      btn_class: "btn--primary"
---
<br>
<h1>
    Personal Projects
</h1>
<br>
{% include feature_row id="epicure" type="left" %}

{% include feature_row id="tjc-notify" type="right" %}

{% include feature_row id="verse-rush" type="left" %}
<br>
<h1>
    School Projects
</h1>
<br>
{% include feature_row %}
