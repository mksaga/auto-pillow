---
layout: post
title: Humble Beginnings!
---

### Let the Games Begin

It's the first week of April, and we've finally started actually working on the project!

We decided to use the mBed microcontroller as the core of the project. At this point, we are trying to tackle the first major piece of the project: sensing the position of a sleeper's head on the pillow.

Found out in lecture today about capacitive sensors that are simple and detect whether something is on top or not. Soldering a wire to the sensor was a bit of a nightmare, but some heat shrink helped save the day. As of now, we can tell whether or not something is on top of the sensor: when we press on it, the reading is ~0.95+, and when nothing is on it, the reading is roughly 0.25 or below. Next step is to get a grid of these sensors working and come up with a way to categorize head orientations based on the sensor readings!
