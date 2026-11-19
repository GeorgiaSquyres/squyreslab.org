---
title: Team
nav:
  order: 2
  tooltip: About our team
---

{% include section.html background="images/background.jpg" dark=true %}

# Lab Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'masters'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Our Pets

{% include section.html %}

{% include list.html data="pets" component="portrait" clickable=false%}

{% include section.html background="images/background.jpg" dark=true %}

# Group Photos

{% include section.html %}

<style>
.lab-photo-gallery {
  display: flex;
  flex-flow: row wrap;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px 14px;
  margin: 1rem 0 2rem;
  width: 100%;
}

.lab-photo-gallery figure {
  display: block;
  flex: 0 0 auto;
  width: min-content;
  max-width: 100%;
  margin: 0;
}

.lab-photo-gallery img {
  display: block;
  height: 220px;
  width: auto;
  max-width: 100%;
  object-fit: contain;
  border-radius: 2px;
}

.lab-photo-gallery figcaption {
  display: block;
  width: 100%;
  min-width: 0;
  margin-top: 6px;
  font-size: 0.85em;
  line-height: 1.35;
  white-space: normal;
  overflow-wrap: anywhere;
}

/* Mobile */
@media (max-width: 600px) {
  .lab-photo-gallery {
    gap: 14px 10px;
  }

  .lab-photo-gallery img {
    height: 160px;
  }
}
</style>

<div class="lab-photo-gallery">

  <figure>
    <img src="/images/group-photos/Day_One.jpeg"
         alt="Week one!"
         loading="lazy">
    <figcaption>Our first week at EMBL! Don't worry, Dilan has her own office now...</figcaption>
  </figure>

  <figure>
    <img src="/images/group-photos/Lab_Halloween.jpeg"
         alt="Lab halloween"
         loading="lazy">
    <figcaption>MSB Halloween costume context: Pel and eDNA. We got second place!</figcaption>
  </figure>

</div>


