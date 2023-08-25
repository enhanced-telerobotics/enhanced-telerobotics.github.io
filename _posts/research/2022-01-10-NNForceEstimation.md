---
layout: page
subheadline: Research
title:  "Vision-based Force Estimation and Haptic Feedback using Neural Networks"
teaser: "Forcep tip force sensing in robot-assisted minimally invasive surgery is challenging due to strict requirements for miniaturization, biocompatibility, and sterilizability. Indirect force estimation is a promising method to measure forces while circumventing these constraints. Much like how humans can estimate forces visually, neural networks can attempt to do something similar. However, there are concerns as to the generalizability of these methods as well as the relative importance of visual information compared to robot kinematic state information as inputs. We characterize the performance of vision-based neural networks with these considerations in mind and quantify the quality of the closed-loop haptic feedback they can provide to the operator."
breadcrumb: false
show_meta: false
categories:
    - research
tags:
    - haptics
    - "deep learning"
image:
    title: nn_force_est_main.png
    thumb: nn_force_est_thumb.png
    homepage: nn_force_est_thumb.png
author: zchua
---

Primary Researcher: Zonghe Chua

<br>
<br>
<div class="row">
<div class="medium-6 columns">
<img src="/images/force_trajectory.gif" alt="Offline NN predictions">
</div>
<div class="medium-6 columns">
Our neural networks are capable of estimating interaction forces offline. In the figure below, the black line is the ground truth force while the green, red, and blue lines are our vision-only, state-only, and vision+state neural networks. We included two benchmarks, an RNN (purple) as well as a physics-based dynamic model (gold). 
</div>
</div>
<br>
<br>
<div class="row">
<p>
We also performed a gradient class activation to understand what visual features were being used by the neural networs to estimate force. Here we see from left to right that in the x-, y-, and z-directions, the neural networks are looking at the shadows and deformation of the silicone material.
</p>
<img src="/images/gradcam.gif" alt="NN gradcam" style="margin:auto;display:block;width=50%;">
</div>

<br>
<br>
We have posted part of the dataset from {% cite ChuaICRA2021 %} online. This can be access via our github repo page [here](https://github.com/enhanced-telerobotics/single_psm_manipulation_dataset).
<br>
<br>

## Published Works 

{% reference ChuaIROS2022 %}

{% reference ChuaICRA2021 %}

## Other Research
{: .t60 }
{% include list-posts entries='3' offset='1' category='research' %}


