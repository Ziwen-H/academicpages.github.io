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
* **Ziwen He**, Marufa Akter Upoma, and Min Y. Pack. "Dual nature of volatility on drop wetting dynamics of acetone–isopropanol mixtures on ultrathin smooth oil films." </i>Physics of Fluids 35, no. 1 (2023).</i> Full text available at <a href="https://doi.org/10.1063/5.0131299"></a>.

* **Ziwen He**, Huy Tran, and Min Y. Pack. "Air entrainment dynamics of aqueous polymeric droplets from dilute to semidilute unentangled regimes." </i>Physics of Fluids 34, no. 11 (2022). </i> Full text available at <a href="https://doi.org/10.1063/5.0130251"></a>.

* **Ziwen He**, Huy Tran, and Min Y. Pack. "Drop bouncing dynamics on ultrathin films." </i>Langmuir 37, no. 33 (2021): 10135-10142. </i> Full text available at <a href="https://doi.org/10.1021/acs.langmuir.1c01510"></a>.

* Tran, Huy, **Ziwen He**, Pooria Pirdavari, and Min Y. Pack. "Interplay of Drop Shedding Mechanisms on High Wettability Contrast Biphilic Stripe-Patterned Surfaces." </i>Langmuir 39, no. 48 (2023): 17551-17559. </i> Full text avaiable at <a href="https://doi.org/10.1021/acs.langmuir.3c03042"></a>.

* Tran, Huy, **Ziwen He**, Jordan Sakakeeny, Yue Ling, and Min Y. Pack. "Oscillation dynamics of drops on immiscible thin liquid films." </i>Langmuir 38, no. 3 (2022): 1243-1251.</i> Full text avaiable at <a href="https://doi.org/10.1021/acs.langmuir.1c03029"></a>.
* 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
