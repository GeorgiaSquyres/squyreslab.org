---
---
{% include section.html dark=true %}

# The Squyres Lab

We use high-resolution live imaging, quantitative analysis, microfluidics, molecular genetics, mathematical modelling, and more to understand how bacteria build biofilms, and how biofilms shape bacteria.

{% capture text %}

Learn about our research interests and ongoing projects in the group.

{%
  include button.html
  link="research"
  text="Research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/squyres-group-video1.gif"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Check out our publications.

{%
  include button.html
  link="publications"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Meet our microbial community!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/EMBL-Heidelberg.jpg"
  link="team"
  title="Our Team"
  text=text
%}
