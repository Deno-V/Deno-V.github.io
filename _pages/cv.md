---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

🎓 Education
======
* Ph.D in *Pattern Recognition and Intelligent Systems*,  Institute of Automation, Chinese Academy of Sciences, 2021-Present
* B.S. in *Automation*, Tongji University, 2017-2021 (Ranked first in my major 1/100)

💼 Internship
======
* Meituan, Intern
  - Work focus: Aspect-based semantic analysis along with graph neural networks, 2021/08 - 2022/02


📄 Publications
======
{% assign sorted_publications = site.publications | sort: 'date' | reverse %}  
<ul>  
    {% for post in sorted_publications %}  
    {% include singleitem.html %}
    {% endfor %}  
</ul>  

🏆 Honors
======
- 2023-2024 Outstanding Student of UCAS
- 2021 Outstanding Graduate of Shanghai
- 2018-2019 National Scholarship
- 2019 First Prize in the National University Students' Electronic Design Competition
- 2019 Second Prize in the East China Region of the NXP Cup Intelligent Vehicle Competition
- 2018 First Prize in the Shanghai Division of the 10th National College Student Mathematics Competition
- 2018 First Prize in the Excellence University Alliance College Student Mathematics Competition
- 2017-2018 National Scholarship
- 2017-2018 Outstanding Student of Tongji University
- others

📚 Mastered Courses
======
- **Mathematics**: Advanced Mathematics, Linear Algebra, Probability Theory, Complex Functions and Integral Transforms, Operations Research, ...
- **Artificial Intelligence**: *Deep Learning*, *Machine Learning*, *Pattern Recognition*, *Text Data Mining*, *Natural Language Processing*, *Principles and Algorithms of Artificial Intelligence*, *Theory and Application of Optimization Algorithms*, Methods of Algorithm Optimization, ...
- **Computer Science**: *Design and Analysis of Computer Algorithms*, C/C++ Programming, Computer Networks, Microcomputer Principles and Interface Technology, Software Technology, ...
- **Engineering**: Signals and Systems, Principles of Automatic Control, Modern Control Technology, Factory Power Supply, Mechanical Drawing, Electrical Machines and Drives, ...
- **Electronics**: Analog Electronic Technology, Digital Electronics, Principles of Circuits, ...
- Others: *Management Psychology*, Legal System of Human Rights, *Optimization and Simulation in Finance*, ...

The courses in *italics* are graduate courses, while the others are undergraduate courses.

- **Ongoing**: Macroeconomics, ...

🧑‍🤝‍🧑 Service and leadership
======
* 2023 President of the IEEE Student Branch at the University of Chinese Academy of Sciences.
* 2021 Class Leader, School of Electronics and Information Engineering, Tongji University.
* 2017-2021 Member of the Technical Promotion Department, Student Union, School of Electronics and Information Engineering, Tongji University.
* 2017-2018 Volunteer services at the Lu Xun Memorial Museum in Shanghai and various marathons across the city.
* others


🛠️ Skills
======
* Programming
  * Python: Proficient in PyTorch, TensorFlow, and other AI-related packages.
  * C: Used C to implement image processing, navigation, and control algorithms in the Intelligent Car Competition and to build a small electromagnetic railgun (2019). Primarily utilized in microcontrollers.
  * Matlab: Applied in mathematical modeling competitions, various signal processing/power electronics/control system simulations, and robot navigation algorithms (2020).
  * Verilog: Used verilog with Vivado in designing FPGA programs.
  * Java & Android: Developed a data sensing and detection app, applied in [this devices](https://onlinelibrary.wiley.com/doi/full/10.1002/smll.202309785).
* Altium Designer: Skilled in designing and soldering circuit boards, including various small power and signal printed circuit boards.
* Digital Painting/Painting: A hobbyist experienced with Photoshop, SAI, acrylic paints, and oil pastels.
* Musics: A long-time fingerstyle guitar enthusiast; erhu player.
* others

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->



