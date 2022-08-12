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

# Land use in Brussels Capital Region (BCR)

<div class="container" id="habitats">
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

# Observed Species

<ul class="nav nav-tabs" id="myTab" role="tablist" id="obsSpecies">
  <li class="nav-item" role="presentation">
    <button class="nav-link active" id="birds-tab" data-bs-toggle="tab" data-bs-target="#birds" type="button" role="tab" aria-controls="home" aria-selected="true">Birds</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="mammals-tab" data-bs-toggle="tab" data-bs-target="#mammals" type="button" role="tab" aria-controls="profile" aria-selected="false">Mammals</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="reptiles-tab" data-bs-toggle="tab" data-bs-target="#reptiles" type="button" role="tab" aria-controls="profile" aria-selected="false">Reptiles and amphibians</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="dragonflies-tab" data-bs-toggle="tab" data-bs-target="#dragonflies" type="button" role="tab" aria-controls="profile" aria-selected="false">Dragonflies</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="butterflies-tab" data-bs-toggle="tab" data-bs-target="#butterflies" type="button" role="tab" aria-controls="profile" aria-selected="false">Butterflies</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="moths-tab" data-bs-toggle="tab" data-bs-target="#moths" type="button" role="tab" aria-controls="profile" aria-selected="false">Moths and ...</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="bees-tab" data-bs-toggle="tab" data-bs-target="#bees" type="button" role="tab" aria-controls="profile" aria-selected="false">Bees, wasps and ants</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="bugs-tab" data-bs-toggle="tab" data-bs-target="#bugs" type="button" role="tab" aria-controls="profile" aria-selected="false">Bugs and leafhoppers</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="beetles-tab" data-bs-toggle="tab" data-bs-target="#beetles" type="button" role="tab" aria-controls="profile" aria-selected="false">Beetles</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="arthropods-tab" data-bs-toggle="tab" data-bs-target="#arthropods" type="button" role="tab" aria-controls="profile" aria-selected="false">Arthropods (other)</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="insects-tab" data-bs-toggle="tab" data-bs-target="#insects" type="button" role="tab" aria-controls="profile" aria-selected="false">Insects (others)</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="flies-tab" data-bs-toggle="tab" data-bs-target="#flies" type="button" role="tab" aria-controls="profile" aria-selected="false">Flies and mosquitoes</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="grasshoppers-tab" data-bs-toggle="tab" data-bs-target="#grasshoppers" type="button" role="tab" aria-controls="profile" aria-selected="false">Grasshoppers and crickets</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="fish-tab" data-bs-toggle="tab" data-bs-target="#fish" type="button" role="tab" aria-controls="contact" aria-selected="false">Fish</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="molluscs-tab" data-bs-toggle="tab" data-bs-target="#molluscs" type="button" role="tab" aria-controls="contact" aria-selected="false">Molluscs</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link" id="invertebrates-tab" data-bs-toggle="tab" data-bs-target="#invertebrates" type="button" role="tab" aria-controls="contact" aria-selected="false">Other invertebrates</button>
  </li>
</ul>


<div class="tab-content" id="myTabContent">

  <div class="tab-pane fade show active" id="birds" role="tabpanel" aria-labelledby="birds-tab">
    There are 1,396,778 observations from the group Birds.
    <img src="/assets/img/maps/BaseMap_natural_Birds.png" alt="Birds map" width="800"/>
    {% include atlas/freqFamilies_Birds.html %}
    {% include atlas/freqSpecies_Birds.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="mammals-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="reptiles" role="tabpanel" aria-labelledby="reptiles-tab">
    There are 46,903 observations from the group Reptiles.
    <img src="/assets/img/maps/BaseMap_natural_ReptilesAmphibians.png" alt="Reptiles" width="800"/>
    {% include atlas/freqFamilies_ReptilesAmphibians.html %}
    {% include atlas/freqSpecies_ReptilesAmphibians.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

  <div class="tab-pane fade" id="mammals" role="tabpanel" aria-labelledby="profile-tab">
    There are 46,903 observations from the group Mammals.
    <img src="/assets/img/maps/BaseMap_natural_Mammals.png" alt="Mammals" width="800"/>
    {% include atlas/freqFamilies_Mammals.html %}
    {% include atlas/freqSpecies_Mammals.html %}
  </div>

</div>
