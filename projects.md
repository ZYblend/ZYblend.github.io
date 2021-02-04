---
layout: page
title: Projects
subtitle: 
share-title: Yu Zheng | Projects
share-description: This is a collection of some personal projects I’ve worked on.
comments: true
carbonads: true
---

This is a collection of some personal projects I've worked on that are easily viewable online. 

## Ongoing Projects
-------------------------------
### ```Resilient Estimation```
- **Phase 1:** (Finished)
1. Optimazition-based false data injection attacks (FDIAs) Design 
2. Resilient L1 observer design and quasi-static stability analysis
3. Related paper: 
- **Phase 2.1:** (Planned)
GAN-based false data injection attacks (FDIAs) design
- **Phase 2.2:** (Ongoing)
Stability analysis for moving-horizon L1 observer

### ```Imu Dead-reckoning```


## Past Projects
-------------------------------
### ```Trajectory Tracking based on Image```
This project is for [Ai-track-at-sea](https://www.challenge.gov/challenge/AI-tracks-at-sea/) competition. We won 2rd place in competition!<br>
Radar-based automatic tracking systems have been a main tool for marine traffic localization, however, emitting radar provides poor cover against adversaries nearby. The development of AI and computer vision has provided a platform for rapid development of solutions for tracking marine traffic by using the passive sensing capability of readily available and inexpensive monocular cameras. <br>
We develop a software: an AI-based computer vision system with capability of real-time tracking. It contains three parts: **Objective detection in image**, **Quadratic-learning camera transformation**, and **Data regression for smoothing**.
<img src="/assets/img/projects/tracking_pipeline.png" width="700"/>

A testing result is shown below:(left:ground truth, right: trajectory tracking)

<img src="/assets/img/projects/Ai-track_result.png" width="600"/>



### ```Secure Path-tracking Control for Non-holonomic WMR```
Nonholonomic wheeled mobile robots (WMRs) have attracted much attention in the past two decades due to its great mobility and the broad range of application. Due to the increasing dependence on IoT devices and wireless communication, the resulting tight coupling of computation, communication and physical components enables malicious agents to inject attacks via the sensors and actuators. <br>
<img src="/assets/img/projects/DDWMR.png" width="300"/>

In this project, we design a secure path-tracking control scheme for WMR: **asymptotically stable path-tracking controller** + **attack-reilient unscented Kalman Filter**.<br>
<img src="/assets/img/projects/Path_tracking_WMR.png" width="300"/>

The simulation codes can be found at [my github](https://github.com/ZYblend/Resilient-path-tracking-control-for-WMR), the result is shown below: <br>
<img src="/assets/img/projects/figure8.png" width="300"/> <img src="/assets/img/projects/Circle_tracking.png" width="350"/>

**Related paper**: Zheng, Yu, and Olugbenga Moses Anubi. "Attack-resilient observer pruning for path-tracking control of Wheeled Mobile Robot." ASME Dynamic Systems and Control Conference (DSCC 2020).

### ```Emergency Control for AUV```

**Related paper**: 
- Zheng, Yu, et al. "A finite state machine based diagnostic expert system of large-scale autonomous unmanned submarine." 2018 IEEE 8th International Conference on Underwater System Technology: Theory and Applications (USYS). IEEE, 2018.
- Wang, Wenjin, et al. "Research and Experiments on Submergence for Self-propelled Model with Positive Buoyancy." The 28th International Ocean and Polar Engineering Conference. International Society of Offshore and Polar Engineers, 2018.
