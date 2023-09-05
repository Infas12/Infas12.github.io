---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- <span class='anchor' id='about-me'></span> -->

# 🙋About Me

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/SWhegPro_500x192.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  <font size=4>SWhegPro: A Novel Robust Wheel-Leg Transformable Robot</font>
  Cunxi Dai, **Xiaohan Liu**, Jianxiang Zhou, Zhengtao Liu, Zheng Zhu and Zhenzhong Jia, **ROBIO 2022**  
  
  [[IEEE](https://ieeexplore.ieee.org/abstract/document/10011955)]
  
  </div>
</div>

<div class='paper-box' width="75%">
  <div class='paper-box-image' width="75%">
    <div>
      <img src='images/SWheg_500x326.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" width="75%">

  <font size=4>SWheg: A Wheel-Leg Transformable Robot with Minimalist Actuator Realization</font>
  C. Dai\*, **X. Liu**\*, J, Zhou\*, Z. Liu, Z. Zheng, Z. Jia, **ICARM 2022**

  [[arxiv](https://arxiv.org/abs/2210.15126)]

  </div>
</div>


# 🤖 Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/WheelLeg_500x294.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>NMPC controller for Wheel-leg robot</font>

  A nonlinear model predictive controller based on ocs2 and ros-control. 
  
  [[video](https://www.bilibili.com/video/BV1Fp4y177D5/?spm_id_from=333.999.0.0&vd_source=eec7130c00a71582de81c4193d7fe763)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/UndergradThesis_500x196.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>RL based whole-body operation controller for qurupedal robots</font>

  My undergraduate thesis. We trained a controller to make the robot climb, lean on the wall, and use its forelimbs to press a point on the wall.

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/DeltaHopper_500x274.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>3-Dof Hopping controller for Delta Hopper Robot</font>

  A hopping controller for CMU GOAT robotic leg. The robot can jump in all directions at desired height and velocity when its orientation is constrained.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/TeachPendant_500x277.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>RoboMaster Teach Pendant</font>

  A Visual-SLAM based teach pendant for Robomaster 'Engineer' robot. 
  
  [[video1](https://www.bilibili.com/video/BV1VM4y1p7JX/?spm_id_from=333.999.0.0&vd_source=eec7130c00a71582de81c4193d7fe763)] [[video2](https://www.bilibili.com/video/BV1Uu411J7pJ/?spm_id_from=333.999.0.0&vd_source=eec7130c00a71582de81c4193d7fe763)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/Robomaster2021_500x196.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>RoboMaster 'Hero' robot and 'Engineer' robot</font>

  Competition robots designed for Robomaster 2021 season. I was responsible for the embedded system software development.

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/OculusROS_500x343.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  
  <font size=4>Oculus-ROS</font>

  ROS Interface for Oculus Quest 2 based on the ROS# Unity plugin and Oculus Unity integration. 

  </div>
</div>



# 🎖 Honors and Awards
- *2021.08*, RoboMaster 2021 University Championship National First Prize(Top 16)
- *2021*, The Undergraduate  Training Program for Innovation and Entrepreneurship Funding (National level)
- *2023.08*, RoboMaster 2023 University Championship National First Prize  (Top 16)

# 📖 Education
- *2023.08 - now*, M.S in Robotics, Carnegie Mellon University, Pittsburgh. 
- *2019.09 - 2023.06*, B.Eng. in Robotics, Southern University of Science and Technology, Shenzhen. 