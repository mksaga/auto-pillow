---
layout: post
title: Integration
date: 30 April
excerpt_separator: <!--more-->
---

It's the week of the reach demo.

Miraculously, in the wee hours of the morning, we were finally able to get the integrated system working. Finally, we could use one mbed to continuously read values from the sensors and activate particular solenoids (and the pump) accordingly. It was such a relief to finally see the system coming together.

<!--more-->

Our algorithm for deciding which side to inflate was very simple, based only on total pressure on each side. If the right side was above a certain pressure, we inflated the top right compartment; similarly, if the left side was above a certain pressure, we inflated the top left compartment.
