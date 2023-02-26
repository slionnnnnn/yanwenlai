---
layout: archive
title: "Publications"
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

