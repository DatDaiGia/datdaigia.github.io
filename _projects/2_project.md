---
layout: page
title: Traffic Sign/Light Detection
description: One of the most challenging project I have worked on. The detection model is required to be robust to objects with different conditions like weather, daytime, lighttime, extreme light, etc. It is also mandatory to achieve optimal threshold in computation for deployment in AGX Driver or ARM64. The number of traffic signs and lights are around 300 classes.
img: assets/img/traffic.png
importance: 2
category: Computer Vision
giscus_comments: false
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/test_traffic_sign_light_out_strimm.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/traffic_demo_trim.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

<div class="caption">
    On the left, a demo we test our model performance on the traffic condition of the inner city, Hanoi. Right, on the highway where our model is required to have the ability to detect the traffic signs with different ranges of distance based on the car speed.
</div>
