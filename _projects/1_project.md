---
layout: page
title: TreeScope - Agricultural Robotics Dataset
description: TreeScope is the first robotics dataset for precision agriculture and forestry addressing the counting and mapping of trees in forestry and orchards (ICRA 2024). 
img: assets/img/treescope-cover.png
importance: 1
category: research
related_publications: einstein1956investigations, einstein1950meaning
redirect: https://treescope.org/
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.youtube.com/embed/GgV1PmLEFeI" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Data collection for forestry, timber, and agriculture relies on manual techniques which are labor-intensive and time-consuming. We seek to demonstrate that robotics offers improvements over these techniques and can accelerate agricultural research, beginning with semantic segmentation and diameter estimation of trees in forests and orchards. We present TreeScope v1.0, the first robotics dataset for precision agriculture and forestry addressing the counting and mapping of trees in forestry and orchards. TreeScope provides LiDAR data from agricultural environments collected with robotics platforms, such as UAV and mobile robot platforms carried by vehicles and human operators. In the first release of this dataset, we provide ground-truth data with over 1,800 manually annotated semantic labels for tree stems and field-measured tree diameters. We share benchmark scripts for these tasks that researchers may use to evaluate the accuracy of their algorithms. Finally, we run our open-source diameter estimation and off-the-shelf semantic segmentation algorithms and share our baseline results.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/treescope.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    TreeScope
</div>