---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

These works provide an overview of my research in multiphase fluid flows.
{% include base_path %}

Upcoming papers:
* Pirdavari, P., Tran, H., **He, Z.**, & Pack, M. Y. (2024). Drainage-induced spontaneous film climbing in capillaries. </i>Physics of Fluids.</i> (Under Review)
* **He, Z.***, Tran, H., & Pack, M. Y. (2024). Capillary wave-assisted collapse of non-Newtonian droplets. </i>Physical Review Letter.</i> (Under Review)
* Tran, H., **He, Z.**, & Pack, M. Y. (2024). Microbubble entrainment on thin liquid films under drop impacts. </i>Journal of Fluid Mechanics.</i> (Under Review)
* Upoma, M. A., **He, Z.**, Tran, H., & Pack, M. Y. (2024). Extensional Rheological Effects of Dye-Polymer Solutions. </i>Physics of Fluids.</i> (Under Review)
* Pirdavari, P., Pourfattah, F., Tran, H., Wang, L., **He, Z.**, & Pack, M. Y. (2023). Experimental and numerical study on the performance index of mixing for low aspect ratio serpentine microchannels. </i>Journal of Micromechanics and Microengineering.</i> (Under Review)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
