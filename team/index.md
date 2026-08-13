---
title: Researchers
nav:
  order: 3
  tooltip: About our researchers
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our research team consists of a Principal Scientific Officer (PSO), a Senior Scientific Officer (SSO), and a Scientific Officer (SO) who work collaboratively to advance the division’s research goals. The PSO provides strategic leadership and oversees project development, while the SSO coordinates ongoing research activities and supervises laboratory work. The SO actively contributes to experimental design, data generation, and analysis, ensuring the successful implementation of our microbial biotechnology research initiatives.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}



{% include section.html %}

{% capture content %}

{% include figure.html image="images/hashem_sir.webp" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/me-1.webp" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
