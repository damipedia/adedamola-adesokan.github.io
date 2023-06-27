---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---
<!---
<H2>Journal Publications</H2>

<ol>
   <li><p align="justify"><b>M. S. Siraj</b>, A. B. Rahman, M. Diamanti, E. E. Tsiropoulou and S. Papavassiliou, "Alternative Positioning, Navigation, and Timing Enabled by Games in Satisfaction Form and Reconfigurable Intelligent Surfaces," in IEEE Systems Journal, doi: 10.1109/JSYST.2023.3268989.</p></li>
  <li><p align="justify"><b>M. S. Siraj</b>, A. B. Rahman, M. Diamanti, E. E. Tsiropoulou and S. Pavassiliou, "Alternative Positioning, Navigation, and Timing enabled by Games in Satisfaction Form and Reconfigurable Intelligent Surfaces", IEEE Systems Journal. (Accepted)</p></li>
</ol>
-->
<H2>Conference Publications</H2>

<ol>
   <li><p align="justify"><b>A. Adesokan</b>, M. S. Siraj, A. S. Penafiel, E. E. Tsiropoulou and S. Papavassiliou, "GAIA: A Dynamic Crowdmapping Framework based on Hedonic Coalition Formation Games", Globecom2023 SAC SN. (Under Review)</p></li>
  <li><p align="justify"><b>A. Adesokan</b>, M. S. Siraj, A. B. Rahman, E. E. Tsiropoulou and S. Pavassiliou, "How to become an Influencer in Social Networks", IEEE ICC'23 - SAC-07 SN Track. (Accepted)</p></li>
</ol>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}