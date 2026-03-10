---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Microbial Biotechnology Lab is committed to transparency and global scientific exchange. Whether you are a prospective graduate student, a fellow researcher, or an industrial partner, we welcome your inquiries. Please use the navigation below to explore our published datasets, current projects, and primary points of contact.

2. The "Innovation-Focused
{%
  include button.html
  type="email"
  text="hashemnib04@yahoo.com"
  link="hashemnib04@yahoo.com"
%}
{%
  include button.html
  type="phone"
  text="+880 1521111532"
  link="+880 1521111532"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https:https://www.google.com/maps/place/National+Institute+of+Biotechnology/"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
