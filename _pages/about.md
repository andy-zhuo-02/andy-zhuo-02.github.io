---
permalink: /
title: "Zhuo An · 卓安"
show_title: false
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="home-intro">
  <h1 class="page__title">{{ page.title }}</h1>
  <p class="home-intro__role">Ph.D. Candidate · Peking University</p>
  <p>At the School of Advanced Manufacturing and Robotics, I study task planning and control of multi-agent systems. Alongside my research, I develop UAV simulation tools and integrate mapping and navigation for quadruped robots.</p>
  <p>My advisor is <a href="https://www.zhongkuili-pku.com/home/" target="_blank" rel="noopener noreferrer">Prof. Zhongkui Li</a>.</p>
  <nav class="home-intro__links" aria-label="Quick links">
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
    <a href="https://github.com/andy-zhuo-02">GitHub</a>
    <a href="#contact">Contact</a>
  </nav>
</div>

<section class="section-card" aria-labelledby="news">
<h2 id="news">News</h2>

<div class="news-item">
  <div class="news-header">
    <span class="news-date">May 2026</span>
    <span class="news-links">
      <a href="https://arxiv.org/abs/2605.07877" class="news-link" target="_blank">arXiv</a>
    </span>
  </div>
  <span class="news-content">New preprint on <a href="https://arxiv.org/abs/2605.07877">LLMs and temporal logic for reliable human-swarm collaboration</a>.</span>
</div>

<div class="news-item">
  <div class="news-header">
    <span class="news-date">Nov 2025</span>
    <span class="news-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/11300826" class="news-link" target="_blank">IEEE Xplore</a>
      <a href="https://arxiv.org/abs/2504.02852" class="news-link" target="_blank">arXiv</a>
    </span>
  </div>
  <span class="news-content">Our paper on <a href="https://ieeexplore.ieee.org/abstract/document/11300826">curvature-constrained motion planning</a> was accepted by <strong>IEEE Transactions on Robotics</strong>.</span>
</div>

<div class="news-item">
  <div class="news-header">
    <span class="news-date">Aug 2025</span>
    <span class="news-links">
      <a href="https://github.com/andy-zhuo-02/XTDrone2" class="news-link" target="_blank">GitHub</a>
    </span>
  </div>
  <span class="news-content">Release <b>repository</b> <strong>XTDrone2</strong>: UAV Simulation Platform based on PX4, ROS2 and Gazebo Ignition.</span>
</div>

<details class="news-archive"><summary>Earlier news</summary>
<div class="news-item">
  <div class="news-header">
    <span class="news-date">June 2025</span>
    <span class="news-links">
      <a href="https://github.com/andy-zhuo-02/go2_ros2_toolbox" class="news-link" target="_blank">GitHub</a>
      <a href="https://www.bilibili.com/video/BV1ioN9zrEpf" class="news-link" target="_blank">Video</a>
    </span>
  </div>
  <span class="news-content">Release <b>repository</b> <i><u>go2_ros2_toolbox</u></i>: A comprehensive ROS2 toolbox for Unitree Go2 EDU robot, providing SLAM and navigation capabilities for autonomous operation.</span>
</div>

<div class="news-item">
  <div class="news-header">
    <span class="news-date">Spring Semester 2025</span>
    <span class="news-links">
      <a href="https://andy-zhuo-02.github.io/teaching/2025-Engineering_Innovation" class="news-link" target="_blank">Info</a>
    </span>
  </div>
  <span class="news-content"><b>Teaching Assistant</b> for <i><u>Engineering Innovation</u></i> course at Peking University</span>
</div>

</details>
</section>

## Publications

<div class="card-grid card-grid--publications">
{% for publication in site.data.publications %}
{% include publication-card.html publication=publication %}
{% endfor %}
</div>

## Open Source Projects

<div class="card-grid card-grid--projects">
{% for project in site.data.projects %}
{% include project-card.html project=project %}
{% endfor %}
</div>

<section class="section-card" aria-labelledby="contact">
<h2 id="contact">Contact</h2>
<ul class="contact-list">
  <li><strong>Email</strong><a href="mailto:zhuoan@stu.pku.edu.cn">zhuoan@stu.pku.edu.cn</a></li>
  <li><strong>GitHub</strong><a href="https://github.com/andy-zhuo-02">andy-zhuo-02</a></li>
  <li><strong>Gitee</strong><a href="https://gitee.com/andy_zhuo">andy_zhuo</a></li>
  <li><strong>Location</strong><span>Beijing, China</span></li>
</ul>
</section>
