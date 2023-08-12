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

**_University of Florida_**              &emsp;     &emsp;                      *_Supervisor: Prof. Shuo Wang_*
 
*  **EMI modeling and reduction of traction inverter for electrical vehicle**  &emsp;  -Supported by Ford Motor Company
  
*  **Modeling and reduction for near magnetic field emission of passive magnetic components**  &emsp;  -Support by NSF
  
  Investigate the near magnetic field emission of the inductor, propose a novel common-mode inductor structure for EMI noise reduction, immunity against external magnetic interference and DM performance improvement
  
*  **EMI models development for non-isolated converters for EV based on CISPR 25**   &emsp;  -Supported by Monolithic Power Systems, Inc.
  
&emsp; 1)  Radiated EMI modeling of high-density DC-DC converters.

&emsp; 2)  Development of prediction model for both conducted EMI and radiated EMI based on circuit simulation and electromagnetic 3D full wave simulation.

&emsp; 3)  Investigation of the monopole antenna’s mechanism in measurement and mismatch between the prediction and the measurement due to test setup.
   


