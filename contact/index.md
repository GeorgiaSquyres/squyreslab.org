---
title: Contact
nav:
  order: 5
  tooltip: Get in touch 
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is in the [MSB department](https://www.embl.org/research/units/molecular-systems-biology/) at the [EMBL](https://www.embl.org/) site in [Heidelberg, Germany](https://www.embl.org/sites/heidelberg/). The EMBL is a hub for interdisciplinary, collaborative molecular biology in Europe, situated in Heidelberg, a romantic and academic city in southwestern Germany. 

Check out our [group page at EMBL](https://www.embl.org/groups/squyres/), and click below to visit us or get in touch! 

{%
  include button.html
  type="email"
  text="squyres@caltech.edu"
  link="squyres@caltech.edu"
%}

{%
  include button.html
  type="address"
  tooltip="EMBL Heidelberg on Google Maps"
  link="https://www.google.com/maps/place/EMBL+Heidelberg/@49.3848322,8.7080197,17z/data=!4m6!3m5!1s0x4797c05e061d3177:0x3fb1d984ca88787c!8m2!3d49.3848322!4d8.7106!16s%2Fg%2F1tgjk76k?entry=ttu&g_ep=EgoyMDI2MDcxOS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/EMBL-Heidelberg.jpg"
  caption="We are based at the EMBL!"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Come visit us in lovely Heidelberg!"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
