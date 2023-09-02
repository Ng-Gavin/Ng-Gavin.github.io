---
layout: project
type: project
image: img/interop/interop.png
title: "Student Unmanned Aerial Systems Competition - Interoptibility Server"
date: 2022
published: true
labels:
  - Drones
  - Ubuntu
  - Machine Learning
  - Virtual Machines
summary: "Interoptibility server for the University of Hawaii Drone Technologies."
---
<p align="center">
  <img class="img-fluid" src="../img/suas/UHDT.png">
</p>

The University of Hawaii Drone Technologies(UHDT) is a Vertically Integrated Project(VIP) which is a multidisciplinary team consisting of mechanical, electrical, and computer engineers. The Student Unmanned Aerial Systems Competition(SUAS) is an annual competition hosted by the Association for Unmanned Vehicle Systems International(AUVSI). In this competition, drones are tasked with autonomously navigating a course and completing a series of tasks. The tasks include autonomously traversing a series of waypoints, identifying and locating targets, mapping a search area, and dropping a remote ground vehicle that delivers a payload.

<p align="center">
  <img class="img-fluid" src="../img/interop/interop.png">
</p>

For this project, our team was split up into several subsystems each assigned to different ascpects of the drone system. I was a memeber of the image processing subsystem. I was tasked with configuring the interoptibility server that would be used for competition. The competition provides the code for running the server, but it must be configured and tested to ensure it works properly with our system. The server is used to deliver the mission results to the judges at the end of the mission. These results include the target's classifications and GPS location, and the map of the search area. The interoptibility code was made to be run through a Unix terminal. As our ground station was a Windows machine, we had to use a virtual machine to run the server. The server was run on a Ubuntu virtual machine.