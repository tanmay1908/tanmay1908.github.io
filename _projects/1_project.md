---
layout: page
title: RoboCare
description: An Alexa-Enabled Human-Robot Interface for Safely Caring for Covid-19 Patients. With K. Shah and M. Mehtaz
img: assets/img/robocare1.jpg
importance: 1
category: fun
---
**Project By:** Tanmay Agarwal, Kathan Shah and Muntaqim Mehtaz \\
**Supervisor:** Dr. Junaed Sattar

<p>This project simulates a TiaGo humanoid robot as a "Home Caretaking Robot". This allows a user to use an alexa in their apartment to command a linked robot anywhere in the world. Built during the coronavirus pandemic as a proof-of-concept to care for contagious patients in a safe manner for hospital staff.</p>

<p>Users can communicate with the robot through two modes:</p>

<ul>
  <li>Hand Gestures - Each room in the simulation is given a number. To tell the robot to go to room 1, hold up one finger; two fingers for room two and so forth</li>
  <li>Voice Commands - The robot can communicate over Alexa. Simply say "Alexa, tell RoboCare to go to room X".</li>
</ul>


Find code and instructions on this <a href="https://github.com/tanmay1908/Covid-HRI">Github Repository</a>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/robocare_overview.jpg" title="Project Infrastructure" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Overview of the project's infrastructure interacting between the robotics stack, cloud stack for Alexa, and computer vision stack for hand gesture detection.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robocare_sim.jpg" title="simulation environment" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/robocare1.jpg" title="TiaGo humanoid robot in sim." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Simulation Environment setup with different rooms. Right: The TiaGo Humanoid Robot completing a task inside the simulator.
</div>
