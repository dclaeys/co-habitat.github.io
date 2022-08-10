---
layout: atlas
title: CO-HABITAT Atlas
permalink: ./atlas
---

<style type="text/css">
#T_882e4 tr:hover {
  background: #f4f4f4;
}
#T_882e4 th {
  color: #fff;
  border: 1px solid #eee;
  padding: 12px 35px;
  border-collapse: collapse;
  background: #00cccc;
  text-transform: uppercase;
  font-size: 18px;
}
#T_882e4 td {
  color: #999;
  border: 1px solid #eee;
  padding: 12px 35px;
  border-collapse: collapse;
  font-size: 15px;
}
#T_882e4 table {
  border: 1px solid #eee;
  border-bottom: 2px solid #00cccc;
}
#T_882e4 caption {
  caption-side: top;
}
</style>

<iframe
  src="/assets/mapW/01_trees.html"
  width="100%"
  height="600"
  title="chart name"
  style="border:none">
</iframe>


<ul class="nav nav-tabs" id="myTab" role="tablist">
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
