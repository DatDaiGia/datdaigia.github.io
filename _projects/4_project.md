---
layout: page
title: Liquors Recommendation
description: In this project, I worked directly with a customer in Japan to develop a recommendation algorithm that suggests similar liquors based on taste coefficients. The algorithm ultimately outperformed a well-known sake recommendation website (https://sakenowa.com/). This work also resulted in two publications in prestigious venues.
img: assets/img/liquor.png
importance: 1
category: Recommendation System
related_publications: true
---

Please find more detail of our algorithms in our 2 publish papers below:

{% cite van2022solving %} and {% cite van2020robust %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/search.png" title="an example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/liquor.png" title="an example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/liquor_res1.png" title="an example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/liquor_res2.png" title="an example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the search bar represents for the taste coefficients we want to find similar liquors.
    Right, the 3 remaining figures are the 3 most similar items that share the cloest distribution to the query input item.
</div>
