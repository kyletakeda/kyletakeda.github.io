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

The inception of our project involved the intricate simulation of traffic dynamics along Dole Street and Ala Moana Blvd, a task meticulously executed through the utilization of Sumo-gui software. To emulate real-world scenarios, we imported GPS coordinates of Dole Street and introduced simulated cars, each representing specific daily traffic patterns. Strategically placing transmitters and affixing receivers atop the simulated vehicles, we established a communication network using designated frequencies. Determining the effective range of these devices, we embarked on a quest to optimize communication between transmitters and receivers within the simulated traffic environment.

Following the successful simulation of traffic patterns, our focus shifted to streamlining data extraction and analysis. To facilitate this, I helped develope a Python code capable of parsing data from Sumo and seamlessly exporting it into MATLAB. This innovative approach not only enhanced efficiency but also obviated the need for hardcoding locations into the program, allowing for adaptability and ease of use.

One of the critical aspects of our project involved calculating the condition number, a task simplified through the dynamic parsing and exporting capabilities of our Python code. By finding the logarithm of the determinant of matrices, we ensured that the power levels were consistently maintained, particularly in the grouping of two cars. This meticulous approach proved instrumental in establishing ideal and efficient communication connections between transmitters and receivers. The intricacies of our method lay in maintaining a harmonious balance, optimizing communication within the simulated traffic environment.

## GitHub Link
If you are interested in seeeing the code I made for this project, here is a link to the python script.
Source: <a href="https://github.com/kyletakeda/ENGRproject/blob/main/main.py"><i class="large github icon "></i>python-script</a>
