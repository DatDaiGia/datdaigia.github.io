---
layout: page
title: Traffic Sign/Light Detection
description: One of the most challenging projects I have worked on involved building a detection model that is robust to varying conditions such as weather, daytime, nighttime, and extreme lighting. The model also needed to be computationally optimal for deployment on AGX Driver or ARM64 platforms. In total, it had to handle around 300 classes of traffic signs and lights.
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
