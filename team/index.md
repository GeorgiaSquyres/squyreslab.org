---
title: Team
nav:
  order: 2
  tooltip: About our team
---

{% include section.html background="images/backgrounds/twitching.gif" dark=true %}

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
  display: grid;
  grid-template-columns: repeat(4, max-content);
  gap: 16px 12px;
  margin: 1rem 0 2rem;
  align-items: start;
}

.lab-photo-gallery figure {
  margin: 0;
  min-width: 0;
}

.lab-photo-gallery img {
  display: block;
  height: 180px;
  width: auto;
  max-width: 100%;
  object-fit: contain;
  border-radius: 2px;
}

.lab-photo-gallery figcaption {
  font-size: 0.85em;
  line-height: 1.35;
  margin-top: 5px;
  max-width: 100%;
}

/* Tablet */
@media (max-width: 900px) {
  .lab-photo-gallery {
    grid-template-columns: repeat(3, max-content);
  }
}

/* Mobile */
@media (max-width: 600px) {
  .lab-photo-gallery {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 12px 8px;
  }

  .lab-photo-gallery img {
    height: 140px;
    max-width: 100%;
  }

  .lab-photo-gallery figure {
    min-width: 0;
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


