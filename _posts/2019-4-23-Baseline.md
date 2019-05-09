---
layout: post
title: Baseline!
date: 23 April
excerpt_separator: <!--more-->
---

The time has finally come for the first big step: the baseline demo.

Velostat has proven to be a very difficult material to work with. It took several nights of trying to get sensible readings from different sized pieces of the material until we finally discovered a key for Velostat: to get good readings, we had to fold the velostat over two or three times. Once we did that, we could finally see observable differences between when we applied pressure versus when we left it alone.
<!--more-->
The Velostat worked reasonably well for us initially, but as we continued, we realized that the readings we were getting were very inconsistent. So, we decided to set that part aside and move on to the next big component of our project: inflating the pillow based on the sensor readings.

The idea behind our project was that based on the readings from the sensors, we could get some idea of the orientation of the sleeping person's head and thus inflate the different compartments of the pillow accordingly. 

We started working with the motor and ran into one barrier after another. We tried using transistors to control the motor with a simple circuit (since we didn't need to control the direction, speed, etc.), but ended up frying multiple power transistors in the process. 

As we worked with the motor, we also realized that we would need a valve for each compartment so that air would not leak out.

Our baseline demo was an embarrassing sight. The motors and solenoid valves did not work, so we had nothing to show for our work. We did get some advice that helped us move forward, though. For one, Kim advised us to use an H-bridge circuit for driving the motor, which turned out to actually work reliably compared to our faulty transistor setup. Rahul also advised us to stop trying to tweak Velostat to get good readings and to just return to the flexible strain resistors (FSRs) that we used initially for our first milestone.
