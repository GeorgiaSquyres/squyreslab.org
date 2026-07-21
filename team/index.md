---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Lab Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'masters'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

Our lab is growing! Interested in joining us? Click here for more info! 

{% include section.html background="images/background.jpg" dark=true %}

# {% include icon.html icon="fa-solid fa-cat" %}Our Pets

{% include section.html %}

{% include list.html data="pets" component="portrait" clickable=false%}


