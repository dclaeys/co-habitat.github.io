---
layout: atlas
title: CO-HABITAT Atlas
permalink: ./atlas
---

<iframe
  src="/assets/mapW/01_trees.html"
  width="100%"
  height="600"
  title="Street trees and Remarkable trees in Brussels Capital Region"
  style="border:none">
</iframe>

# Land use in Brussels Capital Region (BCR)<a id="habiats"></a>

<div class="container">
  <div class="row">
    <div class="col-8">
      <img src="/assets/img/maps/BuildingTypes.png" alt="Birds map" width="800"/>
    </div>
    <div class="col-4">
      Within Brussels Capital Region, most blocks are building blocks. Yet the further away we are from the city center, the more vegetation is present within these conventional building blocks.
    </div>
  </div>
  <div class="row">
    <img src="/assets/img/maps/VegetationCover.png" alt="Birds map" width="800"/>
  </div>

  <div class="row">
    <div class="col">
      <img src="/assets/img/maps/BuiltUpCOLOR.png" alt="Birds map" width="800"/>
    </div>
    <div class="col">
      <img src="/assets/img/maps/NaturalCOLOR.png" alt="Birds map" width="800"/>
    </div>
  </div>

  <div class="row">
    <div class="col">
      ...
    </div>
    <div class="col">
      ...
    </div>
  </div>
</div>

# Observed Species<a id="obsSpecies"></a>

<ul class="nav nav-tabs" id="myTab" role="tablist" id="obsSpecies">
  <li class="nav-item" role="presentation">
    <button class="nav-link active" id="birds-tab" data-bs-toggle="tab" data-bs-target="#birds" type="button" role="tab" aria-controls="home" aria-selected="true">Birds</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="mammals-tab" data-bs-toggle="tab" data-bs-target="#mammals" type="button" role="tab" aria-controls="profile" aria-selected="false">Mammals</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="reptiles-tab" data-bs-toggle="tab" data-bs-target="#reptiles" type="button" role="tab" aria-controls="contact" aria-selected="false">Reptiles and amphibians</button>
  </li>
</ul>


<div class="tab-content" id="myTabContent">
  <div class="tab-pane fade show active" id="birds" role="tabpanel" aria-labelledby="home-tab">
  There are 1,396,778 observations from the group Birds.

  <img src="/assets/img/maps/BaseMap_natural_Birds.png" alt="Birds map" width="800"/>

  {% include atlas/freqFamilies_Birds.html %}

  {% include atlas/freqSpecies_Birds.html %}

  </div>
  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">

  There are 46,903 observations from the group Mammals.

  <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>

  {% include atlas/freqFamilies_Mammals.html %}

  {% include atlas/freqSpecies_Mammals.html %}

  </div>
  <div class="tab-pane fade" id="reptiles" role="tabpanel" aria-labelledby="contact-tab">...</div>
</div>
