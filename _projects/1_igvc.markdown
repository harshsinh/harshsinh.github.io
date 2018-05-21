---
layout: page
title: IGVC
description: Intelligent Ground Vehicle Challenge
img: /assets/img/projects/igvc/igvc.jpg
---

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/projects/igvc/igvc.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    Daksh our robot, a NexRobotics' 0xDelta
</div>

You can find the report for the project at : [Report](/assets/docs/igvc17.pdf)

[Intelligent Ground Vehicle Challenge](http://igvc.org) is a competition organised by [AUVSI](auvsi.org) which is aimed at developing prototype self driving cars. The competition pits teams from around the world against each other on arenas like the one shown below. Teams are supposed to develop different algorithms to autonomously traverse the arena using any method possible.

Our team began working for this competition in the December of 2016, and we aim to take part in the 2018 edition of the competition. Our inital approach was to use a LiDAR and fuse its data with IMU and GPS to develop a global map. This global map was also to contain obstacles from the lanes. We were also segmenting out the lanes using different classical Image Processing Techniques and then adding to the grid map generated from the fused data before. The resultant grid map was then planned on, which gave us the final trajectory to track.

I was working on the LiDAR-IMU-GPS fusion part of the problem, we first implemented the system on indoor environments and then took it outside.
Some of the results from the project are attched below.

<div class="img_row">
    <img class="col one" src="{{ site.baseurl }}/assets/img/1.jpg" alt="" title="example image"/>
    <img class="col one" src="{{ site.baseurl }}/assets/img/2.jpg" alt="" title="example image"/>
    <img class="col one" src="{{ site.baseurl }}/assets/img/3.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.


<div class="img_row">
    <img class="col two" src="{{ site.baseurl }}/assets/img/6.jpg" alt="" title="example image"/>
    <img class="col one" src="{{ site.baseurl }}/assets/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above:

    <div class="img_row">
      <img class="col two" src="/img/6.jpg"/>
      <img class="col one" src="/img/11.jpg"/>
    </div>
