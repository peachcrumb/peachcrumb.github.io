---
layout: project
type: project
image: img/akaji.jpeg
title: "Sculpture 2D Mediums Study"
date: 2024
published: true
labels:
  - architecture
  - SoA 100
  - sculpture

summary: "The ARCH 100 class was tasked with creating our own interpretations of the Bumpei Akaji statue at RISE."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
</div>

During the 'tools' module of ARCH 100, we were instructed to observe the Bumpei Akaji statue in front of the RISE building, and capture a  reference image while being able to explain our intentions behind the angle we chose. 

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

[More information on the sculpture](https://www.hawaii.edu/news/2024/06/15/akaji-sculpture-dedication-rise-grand-opening/).
