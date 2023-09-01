---
layout: project
type: project
image: img/suas/suas.png
title: "Student Unmanned Aerial Systems Competition - Computer Vision"
date: 2022-Present
published: true
labels:
  - Drones
  - Python
  - Machine Learning
  - Computer Vision
summary: "My team developed an autonomous drone for the Student Unmanned Aerial Systems Competition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The Student Unmanned Aerial Systems Competition(SUAS) is an annual competition hosted by the Association for Unmanned Vehicle Systems International(AUVSI). In this competition, drones are tasked with autonomously navigating a course and completing a series of tasks. The tasks include autonomously traversing a series of waypoints, identifying and locating targets, and dropping payloads cooresponding to each target. This is done as a simulated mission of package delivery to a remote location.

For this project, our team was split up into several subsystems each assigned to different ascpects of the drone system. I was the lead of the Image Proccesing subsystem. My subsystem was tasked with creating a system that could identify and locate targets on the ground using the drone's camera. This was done using a combination of computer vision and machine learning. 

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
