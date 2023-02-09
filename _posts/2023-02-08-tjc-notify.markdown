---
layout: posts
title:  "True Jesus Church Notify"
date:   2023-01-17 02:01:01 -0800
categories: jekyll update
permalink: "/tjc-notify"
---
<p align="center">
  <img src="https://noah-ku.github.io/portfolio/assets/images/tjc_notify_mockup2.png?raw=true" alt="tjc-mockup"/>
</p>

True Jesus Church (TJC) Notify is a project that I created in 2022. It is an app dedicated to the members of True Jesus Church in Pacifica.

## Overview

<p align="center">
  <img src="https://noah-ku.github.io/portfolio/assets/images/tjc-notify-5.png?raw=true" width="300" height="300" alt="tjc-database"/>
</p>

TJC Notify is an iOS app written in JavaScript that allows users to see their local church schedule with realtime changes. Any manual database updates such as swaps or substitutes will be automatically seen on everyone's phones. This is different from the original email format for previous church schedules. The app is currently in beta testing and is being used by a select few members.
<br>
<br>
<br>

<p align="center">
  <img src="https://noah-ku.github.io/portfolio/assets/images/tjc-notify-1.png?raw=true" alt="tjc-ios"/>
</p>

The schedules are currently generated on Google Sheets and sent to everyone through email, but a goal for this project is to automatically create randomized schedules given certain constraints. An algorithm to create these schedules has been coded using Java, but it still needs to be implemented with the app so that schedules will automatically generate months in advance.

## List of Notable Features

> * Weekly Push Notifications
> * User tokens for iOS devices
> * Firebase Authentication for user logins
> * Algorithm to generate schedules
> * Firebase Database to store schedules
> * Modified Firebase rules for increased security
> * Admins can send announcements to everyone

## List of Future Goals

> * Automatic swapping/substitution
> * Log in using Google or Facebook accounts
> * History log to store old schedules
> * Add Android support
