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

* **Ziwen He**, Marufa Akter Upoma, and Min Y. Pack. "Dual nature of volatility on drop wetting dynamics of acetone–isopropanol mixtures on ultrathin smooth oil films." *Physics of Fluids 35, no. 1 (2023).* Full text available at <a href="https://doi.org/10.1063/5.0131299">{link}</a>.

* **Ziwen He**, Huy Tran, and Min Y. Pack. "Air entrainment dynamics of aqueous polymeric droplets from dilute to semidilute unentangled regimes." *Physics of Fluids 34, no. 11 (2022).* Full text available at <a href="https://doi.org/10.1063/5.0130251">{link}</a>.

* **Ziwen He**, Huy Tran, and Min Y. Pack. "Drop bouncing dynamics on ultrathin films." *Langmuir 37, no. 33 (2021): 10135-10142.* Full text available at <a href="https://doi.org/10.1021/acs.langmuir.1c01510">{link}</a>.

* Upoma, M. A., **He, Z.**, Tran, H., & Pack, M. Y. (2024). Extensional Rheological Effects of Dye-Polymer Solutions. *Langmuir.* Full text available at <a href="">{link}</a>

* Pirdavari, P., Pourfattah, F., Tran, H., Wang, L., **He, Z.**, & Pack, M. Y. (2024). Experimental and numerical study on the performance index of mixing for low aspect ratio serpentine microchannels. *Engineering Research Express.* Full text available at <a href="">{link}
  
* Boxun Huang, Steven V. Iasella, Meenal Rathi, Joseph Hassler, Clara O. Ciutara, **Ziwen He**, David C. Morse, and Joseph A. Zasadzinski. "New experiments and models to describe soluble surfactant adsorption above and below the critical micelle concentration." *Journal of Colloid And Interface Science (2024).* Full text available at <a href="https://doi.org/10.1016/j.jcis.2024.07.204">{link}</a>.
  
* Tran, Huy, **Ziwen He**, Pooria Pirdavari, and Min Y. Pack. "Interplay of Drop Shedding Mechanisms on High Wettability Contrast Biphilic Stripe-Patterned Surfaces." *Langmuir 39, no. 48 (2023): 17551-17559.* Full text avaiable at <a href="https://doi.org/10.1021/acs.langmuir.3c03042">{link}</a>.

* Tran, Huy, **Ziwen He**, Jordan Sakakeeny, Yue Ling, and Min Y. Pack. "Oscillation dynamics of drops on immiscible thin liquid films." *Langmuir 38, no. 3 (2022): 1243-1251.* Full text avaiable at <a href="https://doi.org/10.1021/acs.langmuir.1c03029">{link}</a>.

  
Upcoming papers:

* Pirdavari, P., Tran, H., **He, Z.**, & Pack, M. Y. (2024). Drainage-induced spontaneous film climbing in capillaries. *Physics Review Fluids.* (Under Review)

* **He, Z.**, Tran, H., & Pack, M. Y. (2024). Capillary wave-assisted collapse of non-Newtonian droplets. *Physics of Fluids.* (Under Review)

* Tran, H., **He, Z.**, & Pack, M. Y. (2024). Microbubble entrainment on thin liquid films under drop impacts. *Journal of Fluid Mechanics.* (Under Review)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
