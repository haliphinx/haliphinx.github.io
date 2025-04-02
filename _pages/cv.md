---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Ottawa, 2025 (expected)
* M.S. in Computer Science, University of Ottawa, 2020
* B.S. in Computer Science, HUazhong University of Science and Technology, 2017

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Work experience
======
* Research Assistant <span style="float: right;"><small>Spet 2020-Present</small></span>
  * University of Ottawa
  * Computer Vision, 4D Reconstruction, SLAM under dynamic environment, RVOS.

* Computer Vision Research Intern <span style="float: right;"><small>Spet 2021-Apr 2022</small></span>
  * National Research Council Canada ([NRCC](https://nrc.canada.ca/en))
  * Real-world computer vision tasks, including semantic segmentation, pedestrian detection and tracking, and trajectory prediction.

* Distributed Systems Intern <span style="float: right;"><small>Spet 2018-Dec 2018</small></span>
  * [Wind River Systems, Inc.](https://www.windriver.com/)
  * Cloud computing system contributions (based on OpenStack) and automated cloud system installation.
    
* Data Analysis Intern <span style="float: right;"><small>May 2018-Sept 2018</small></span>
  * Environment and Climate Change Canada ([ECCC](https://www.canada.ca/en/environment-climate-change.html))
  * Data analysis and river water levels prediction in the Ottawa region.
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* [M5D-GS](https://github.com/haliphinx/M5D-GS) <span style="float: right;"><small>2024</small></span>
  * Developed a 3D Gaussian splatting-based method for 4D dynamic object representation.
  * Decoupled object motion from deformation to improve processing of large-motion objects.
  * Proposed a novel dataset for large-motion objects.

* [TCE-RVOS](https://github.com/haliphinx/TCE-RVOS) <span style="float: right;"><small>2023</small></span>
  * Developed a multi-modal approach for referring video object segmentation
  * Enhanced the ability to understand temporal context.

* Vulnerable Individual-Aided Smart Crossroad System <span style="float: right;"><small>2022</small></span>
  * Implemented pedestrian detection and classification from surveillance images.
  * Estimated and predicted trajectories for vulnerable individuals (elderly, pregnant, and disabled people).
  * Incorporated with the traffic light system to control the green light duration.
 
* UAV-Based Railway Inspection <span style="float: right;"><small>2021</small></span>
  * Segmented railway tracks and water surfaces from UAV images to prevent water overflow onto the tracks.
  * Calibrated GPS information to align images from different conditions and seasons, for risk level analysis.

* DOE-SLAM <span style="float: right;"><small>2020</small></span>
  * Estimated the camera pose and object motion simultaneously.
  * Recovered the camera pose from object motion during obstruction.

* [Dynamic Object SLAM](https://github.com/haliphinx/Object_ORB_SLAM) <span style="float: right;"><small>2019</small></span>
  * Based on ORB-SLAM and Mask R-CNN to reconstruct different object models separately, and improve the accuracy in dynamic environments.

* [Sequence Based SLAM](https://github.com/haliphinx/SEQ_ORB_SLAM2) <span style="float: right;"><small>2019</small></span>
  * Selected the sequence based method with sequence descriptor to reduce the time usage for loop detection.  
  
