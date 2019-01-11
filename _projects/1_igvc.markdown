---
layout: page
title: IGVC
description: Intelligent Ground Vehicle Challenge
img: /assets/img/projects/igvc/IGVC_IITK_Logo.png
---

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/projects/igvc/igvc-min.jpg" alt="" title="Daksh"/>
</div>
<div class="col three caption">
    Daksh our robot, a NexRobotics' 0xDelta
</div>

You can find the report for the project at : [Report](/assets/docs/DesignReport.pdf)

[Intelligent Ground Vehicle Challenge](http://igvc.org) is a competition organised by [AUVSI](auvsi.org) which is aimed at developing prototype self driving cars. The competition pits teams from around the world against each other on arenas like the one shown below. Teams are supposed to develop different algorithms to autonomously traverse the arena using any method possible.

Our team began working for this competition in the December of 2016, and we took part in the 2018 edition of the competition, where we secured the **5th** position in the desing challenge and overall we placed **12th** internationally.

Our inital approach was to use a LiDAR and fuse its data with IMU and GPS to develop a global map. This global map was also to contain obstacles from the lanes. We were also segmenting out the lanes using different classical Image Processing Techniques and then adding to the grid map generated from the fused data before. The resultant grid map was then planned on, which gave us the final trajectory to track.

We have evolved much from then, you can check us out on [Github](https://github.com/IGVC-IITK) or take a stroll on our [website](https://igvc-iitk.github.io/).

While on the team I worked on various parts of the problem from Sensor Fusion, Computer Vision to overall system Integration. As of now I am not actively working on the team but as a mentor.

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/projects/igvc/localization-mapping-min.png" alt="" title="LocalizationMapping"/>
</div>
<div class="col three caption">
    A screenshot from our recent indoor demonstration of autonomous waypoint navigation.
</div>