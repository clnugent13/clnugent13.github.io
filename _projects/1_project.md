---
layout: page
title: Indigenous Placenames of Massachusetts
description: Digital Humanities Project in Progress
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Maps have long been used as a tool of colonialism, dividing up the world and demarcating arbitrary borders. Maps have also been used by the colonial apparatus in the process of sustaining settler colonial geographies in North America. This can be seen for example in the mid-seventeenth century map of Massachusetts (below) that uses cartography to justify the new colonial borders. In this context, maps have been used as evidence of the ‘firsting’ and ‘lasting’ processes described by Jean O’Brien. Maps can demonstrate the apparent ‘lack’ of Indigenous people left, in what has been wielded as ‘proof’ that there are no longer any ‘real’ Indigenous people left. Much like the local literature explored by Jean M. O’Brien, maps were used in the process of removing Indigenous people from their ancestral lands. Maps have been used, alongside narratives, to demonstrate the ‘truth’ of the myth of the vanishing/disappeared Native. Cartography can be used to write Indigenous communities out of existence, in the sense that their absence from dominant mapping regimes constitutes an erasure. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/12.jpg" title="1665-ma-map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A 1665 map commissioned by the government of Massachusetts to justify the colony’s northern and southern boundaries. 
</div>
Cartographies of empire have been instrumental in the dispossession of Indigenous people. Truly decolonial mapping must go beyond anti-colonial mapping in seeking to reclaim plant-based, ancestral, Indigenous knowledge while also enacting the contemporary world-making practices of Indigenous and colonized people in the present. In fact, some of the most effective forms of decolonial mapping entails the creation of maps that are only intended to be seen by Indigenous people. A decolonial geography focuses on the reclamation of Indigenous ontologies of place that predate the colonial cartographic framing of Indigenous lands. Even some maps projects that strive to contest dominant understandings can end up reproducing the settler colonial project. This can be seen in projects that adhere to the official borders of the United States government, which ends up normalizing the colonial boundaries of space. This project seeks to consider the complications inherent in making maps, and to provide maps that better reveal the Indigeneity of the landscape of Massachusetts.

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

<iframe width="700" height="600" allow="local-network-access; geolocation" title="Indigenous Placenames of Massachusetts" src="https://nu.maps.arcgis.com/apps/mapviewer/index.html?configurableview=true&webmap=7ce475ce134b4a6796586ac5bdea046b&theme=light&scroll=false&center=-71.71613720703017,42.26656047051537&scale=2311162.217155" ></iframe>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
