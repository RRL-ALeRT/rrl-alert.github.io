---
layout: post
title: Archimedischer Sandkasten!
subtitle: Kids controlling Spot
author: Maximillian Kirsch
categories: Demonstrations
banner:
  video:
  loop: true
  volume: 0.8
  start_at: 8.5
  image: "/assets/images/"
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: Spot Parkour Demo
sidebar: []
---

Today our spot was located at the Archimedean sandbox on the Katschhof. Children were given the opportunity to steer spot through a parkour with gestures.

## The Parkour

![Parkour](/assets/images/Sandkasten_0.jpg "The Parkour")

We have built a small parkour through which spot must be navigated. The operator stood on an elevated position in view of spot and screens on which the camera images of the spot were displayed.

## Gesture Detection

![Gestures](/assets/images/gestures.png "Gesture Detection")

The gesture detection was implemented with `mediapipe`. The available commands are straight ahead, back and turn left/right. The instructions were visualized via a GUI.