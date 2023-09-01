---
layout: project
type: project
image: img/AlaMoanaBlvd.png
title: "Sumo-gui Simulation"
date: 2022
published: true
labels:
  - Sumo-gui
  - Matlab
  - python
summary: "A simulation of Dole Street traffic for project ENGR 296/396."
---

<img class="img-fluid" src="../img/Screenshot (1).png">

The project first made a simulation of traffic on Dole Street and Ala Moana Blvd using Sumo-gui software. We imported the gps coordinates of Dole Street and then added the simulated cars to act as certain scinarios of daily traffic patterns.
Transmitters were placed in certain areas and the cars have receivers placed on top of them. They communicate using certain frequencies and using distances we would find the effective range of these devices.

After making the traffic pattern, we created a python code that can parse data from sumo and export data into matlab.
This makes finding condition number easier so you do not have to hard code locations into program.
Finally, we will find the logarithm of the determinant of matrix and need to keep power consistent with the grouping of two cars. This makes the connections between the transmitter and receiver ideal and effecient communcation between them.

Source: <a href="main.py"><i class="large github icon "></i>python-script</a>
