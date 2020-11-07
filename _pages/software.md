---
layout: single
title: "Software"
permalink: /software/
author_profile: true
---

# 1. 3D Visualization of Automated Warehouse

----

This is a visualization tool that was built for simulating an automated warehouse. There are shelves that contain goods, and the warehouse robots move shelves to the pickup station to drop off goods. After delivering goods, the robots put shelves back. 

## Components:

1. obstacle (walls): an object that an agent cannot go through
2. stations: where the robot deliver goods to
3. shelves: holders for goods; they are moved by robots
4. robots: with an actuator that can push shelves up, and then move them around. Can rotate in 360 degrees.
5. Products on shelves: customizable, if you have the 3D models ready. Require manual modification of the software for now. Buttons for uploading and customizing goods will be added soon.

## Functions :

1. Free view camera, control the view with mouse and W,A,S,D keys.

2. Load local files for agent plan and warehouse map

3. Socket interface available for receive agent actions from a real-time solver

4. Physics Engine that enables the simulation of collisions, velocity and accelerations of objects.

   

## Video Demo:



