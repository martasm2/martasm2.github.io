---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<a href='https://martasm2.github.io/files/MartaMarkowiczCV_Feb25.pdf'>View as PDF</a>

<!-- # Contact -->
Email: <a href='mailto:martasm2@illinois.edu'>martasm2@illinois.edu</a><br>
LinkedIn: <a href='https://www.linkedin.com/in/marta-markowicz/'>marta-markowicz</a>
<br>
<br>

# Education
* Ph.D. in Computer Science
  * University of Illinois Urbana-Champaign, 2021-Present
* B.S. in Computer Science, GPA 3.9 
  * University of Minnesota Twin Cities, 2017-2021
<br>
<br>


# Skills and Relevant Coursework
**Robotics**: Motion planning, SLAM, Kalman Filter, Kinematics, Computer Vision, Autonomous Vehicles<br>
**Machine Learning**: Deep Learning, Reinforcement Learning<br>
**Programming Languages**: C++, Python, Java, Node.js, SQL<br>
**Frameworks and Environments**: ROS, Gazebo, Linux, Git, CUDA, OpenGL, AWS, Qt<br>
**Electronics**: Microcontrollers, Real-time Systems, Arduino, Altium Designer
<br>
<br>


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<br>
<br>


# Posters
[1] M Markowicz, M Lusardi, S Ashur, J Motes, M Morales, S Har-Peled, NM Amato, "<a href="https://ras.papercept.net/conferences/conferences/ICRAX24/program/ICRAX24_ContentListWeb_3.html\#weint1s_54">SPITE: Simple Polyhedral Intersection Techniques for modified Environments</a>," 40th Anniversary of the IEEE International Conference on Robotics and Automation, Rotterdam, Netherlands, September 2024.
<br>
<br>


# Work experience
**Robotics Graduate Researcher**, 2021-Present<br>
<em>Advisor: Dr. Nancy Amato, University of Illinois<em><br>
* Conducting research on motion planning algorithms for dynamic and uncertain environments using C++ and ROS
* Developed SPITE, a novel dynamic roadmap for replanning in changing environments, achieving up to 60% faster
updates with significantly less pre-processing [C.1]
* Further optimizing dynamic planning through lazy collision evaluation, parallelization, and collision approximation
* Constructing novel temporal planning techniques to integrate with dynamic roadmaps, enabling safer and more
reliable autonomous navigation around predicted obstacle trajectories.
* Open sourcing Parasol Planning Library and benchmarking planning algorithms

**Robotics Research Assistant**, 2017-2021<br>
<em>Advisor: Dr. Stephen J. Guy, University of Minnesota</em><br>
* Developed novel space-time path planning algorithm for dynamic environments
* Leveraged safe intervals to achieve asymptotic optimality with temporal sampling-based planning

**Autonomy Software Design Intern**, Jun-Sept 2020<br>
<em>Caterpillar</em>
* Designed software for autonomous soil compactor testing, improving efficiency in field testing operations
* Enabled real-time remote management of five machines by building user interface in C++ using Qt framework
* Enhanced productivity of equipment testers by reducing on-site monitoring requirements by 40%

**Software Development Intern**, Jan-Mar 2019<br>
<em>Cybercom Poland</em>
*  Developed proof-of-concept solutions integrating hardware and cloud-based software *ystems
* Designed Arduino module with water sensors and implemented AWS Lambda functions for real-time data
collection and monitoring
* Achieved a 60-hour monthly time savings for city technicians in pipe inspection workflows
<br>
<br>


# Projects
**Autonomous Vehicle Motion Planning**, Spring 2024<br>
<em>Tools: ROS, Gazebo, Git</em>
* Designed and implemented motion planning components for Polaris GEM e2 vehicle using Hybrid A* and Model
Predictive Control (MPC).
* Developed solutions for road driving and parking scenarios, incorporating a dynamic vehicle model to optimize
trajectory planning.

**Real-Time Systems for Path Planning**, Fall 2021<br>
<em>Tools: Autoware</em>
* Engineered a resource scheduling algorithm for autonomous vehicle path planning using Autoware
* Enhanced planning efficiency by parallelizing tasks with virtual gang scheduling, achieving an 8% improvement in
execution time

**Model-based reinforcement learning algorithm for exploration**, Fall 2021<br>
<em>Tools: MuJoCo, PyTorch</em>
* Implemented Model-Ensemble Trust-Region Policy Optimization for learning dynamics and policy
* Enhanced convergence speed by 14% through integration of Proximal Policy Optimization (PPO) and model
discrepancy evaluation

**Solar Vehicle Project: Controls**, 2017-2019<br>
<em>Tools: Altium, FreeRTOS</em>
* Led a team of five to design and fabricate a PCB for a steering wheel control system using Altium
* Programmed real-time functionality with FreeRTOS, communicating via a CAN bus
* Troubleshot issues during international race, ensuring system reliability under competitive conditions
<br>
<br>


# Honors and Wards
**Broadening Participation in Computing Fellow**, 2022-Present<br>
<em>University> of Illinois</em>
* Mentoring undergraduate women pursuing research, fostering growth in technical and academic skills
* Running CS Student Ambassadors/Research Scholars (CS STARS) for engaging students in research and outreach

**Andrew and Shana Laursen Fellowship**, 2021<br>
<em>University of Illinois</em>
* Awarded to top graduate students in recognition of academic excellence and promise in advanced research
* Utilized fellowship support to develop novel planning techniques for robots in unpredictable environments

**Hopper-Dean Scholarship honoring Dr. Vipin Kumar**, 2020<br>
<em>University of Minnesota</em>
* Honored for academic excellence and outstanding contributions to undergraduate research
* Conducted research advancing space-time navigation algorithms, improving efficiency and scalability
<br>
<br>


# Mentoring
**Parasol Lab**, 2022-Present<br>
<em>University of Illinois</em>
* Sarah Dowden (Undergrad): Mentoring in robotics planning, leading to successful implementation of temporal
features and simulation testing for SPITE project
* Jin Fan, Relena Li (Undergrads): Guided students in developing and open-sourcing planning library, resulting in
comprehensive algorithm benchmarking
* Andrew Kindratenko, Sanjay Selvam, Aashini Sanapala (High School students): Taught students motion planning
fundamentals, enabling them to contribute to algorithm benchmarking research

**CS Student Ambassadors/Research Scholars**, 2022-Present<br>
<em>University of Illinois</em>
* Mentoring up to 50 undergraduates a semester on research pursuits, coursework, and career advice
* Awarded Broadening Participation in Computing Fellowship in recognition of mentorship

  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

