---
layout: archive
title: "Research Experience"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&tzom=300&user=j0mw7EAAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* H. Chen, T. Shi, Q. Huang, X. Xiang, C. Li, W. Li, X. He, "An impedance-based islanding detection method for DC microgrid with multiple distributed generators," in CSEE Journal of Power and Energy Systems, doi: 10.17775/CSEEJPES.2022.00020.
* Q. Huang, H. Chen, X. Xiang, C. Li, W. Li, and X. He, “Islanding detection with positive feedback of selected frequency for DC microgrid systems,” IEEE Trans. Power Electron., vol. 36, no. 10, pp. 11800–11817, Oct. 2021.
* H. Chen, Q. Huang, W. Li, X. Xiang, H. Luo and X. He, "An Impedance-Based Islanding Detection Method for DC Microgrids with multiple DGs," 2020 4th International Conference on HVDC (HVDC), Xi'an, China, 2020, pp. 1025-1030.
* Q. Huang, C. Li; H. Yang; Y. Dong; W. Li; X. He; W. Zhang; J. Han, "Islanding Detection Methods Based on Self-oscillation of Particular Frequency in DC Distribution Systems," 2020 IEEE Applied Power Electronics Conference and Exposition (APEC), New Orleans, LA, USA, 2020, pp. 574-580, doi: 10.1109/APEC39645.2020.9124587.

* DC Microgrid Operation and Fault Detection                                    Nov. 2018-present
1)	Virtual damping control for improvement of dynamic performance in DC microgrid
2)	Islanding detection method for safe operation in the abnormal condition in DC microgrid
3)	Seamless transfer strategy at islanding event for improvement of reliability and quality of power supply
Outcomes: proposed two DC-based islanding detection methods (one patent granted, one patent under application, one conference (APEC) paper accepted, two papers to be reviewed)
Proposed one virtual damping control strategy for DC microgrid (one Chinese transaction paper accepted, one patent under application)
* Motor Calibration and Automatic Calibration Platform Design for Electrical Vehicle   Jan. 2018-Sep. 2018
Intern in Leadrive Technology (Shanghai) Co.                               Supervisor: Dr. Changjin Liu
Main activities and responsibilities:
1)	Design test procedure of 9 kinds of parameters of a motor for efficient and accurate electrical drive control
2)	Design an automatic motor calibration platform for measurement, data process, equipment protection
3)	Hardware design and software design for the auto-calibration system in LABVIEW
Outcomes: 30+ motors auto-calibrated, 700+ hours safe operation, increased efficiency (2 person/30days →1 person/3 days), improved accuracy (torque error 5%~10%→less than 5%)
* 2017 National Undergraduate Electronics Design Contest                        May 2017-Sep. 2017
Main activities and responsibilities:
1)	Design and implementation of AC microgrid simulator consisting of two inverters
2)	Implementation of specific operating requirements such as efficiency, control strategy, etc.
3)	Hardware design for the power circuit, including parameter design, PCB layout, and device selection and software design and debugging for the control system
Outcomes: Second Prize in the contest of China and First Prize in the contest of Hunan Province

title: "Research"
