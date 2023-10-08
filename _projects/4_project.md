---
layout: page
title: Scuba Diver Motion Prediction 
description: The world's first underwater motion prediction algorithm. With M. Fulton and J. Sattar
img: assets/img/diverpred1.jpg
importance: 3
category: research
---

**Authors:** Tanmay Agarwal, Michael Fulton and Junaed Sattar

Motion prediction for the underwater domain is much more complex than on the ground. Your agents (scuba divers) can move in 6 degrees of freedom, images have a constant blue background, and IMU measurements are noisy and unreliable.

When aquatic robots try to follow human scuba divers in this environment, they often lose track of humans when they turn. To address this proble, we developed a novel perception framework to predict the future trajectory of scuba divers in real-time. By predicting the motion of their target, this module aims to allow aquatic robots to anticipate the movement of humans and be able to follow them better as they dive.

Paper published in IROS 2021 <a href="https://ieeexplore.ieee.org/document/9636374">here</a>.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/diverpred_model.jpeg" title="Model Architecture" class="img-fluid rounded z-depth-1" %}
        
        <div class="caption">
            Model architecture for the motion prediction framework.
        </div>
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/diverpred1.jpg" title="sample output 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/diverpred2.jpg" title="sample output 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample Outputs from the motion prediction algorithm. Darker colors are more in the future.
</div>