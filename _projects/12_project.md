---
layout: page
title: Panda Arm Simulator
description: Robot simulator in C++
img: assets/img/panda.gif
importance: 2.5
category: 
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/panda.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample Panda robot simulation sequence.
</div>

During my internship at Telekinesis AI, I developed a custom, flexible simulator for the Franka Emika Panda robot using the 3D dynamics simulator Gazebo and its C++ plugins. The project involved learning the Gazebo software and the basics of URDF files, which describe a robot's model. I then wrote the C++ code to simulate the Panda robot in Gazebo, using the appropriate plugins to enable communication between client-side (user) and server-side (robot) operations. 
