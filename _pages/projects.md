---
layout: page
title: projects
permalink: /projects/
<!--description: A growing collection of your cool projects.-->
---

{% for project in site.projects %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}

### other relevant projects

* CNN-EKF: Relocalizing robots with cheap sensors. \| [report/paper]() \| [code]()
* Warehouse Inventory Management with Quadrotors \| [presentation](/assets/docs/wic.pdf) \| [code](https://github.com/harshsinh/warehouse-quad)
* Human Tracking and Following Quadrotor \| [report](/assets/docs/ae640a-report.pdf) \| [code](https://github.com/harshsinh/follow-quad)
* Single Image Super Resolution via Sparse Representation \| [report](/assets/docs/ee698k-report.pdf)
* Robocon'16: Energy Efficient Robotics \| [web-report](http://students.iitk.ac.in/robocon/docs/doku.php)
* Autonomous Underwater Vehicle \| [website](www.auviitk.com)