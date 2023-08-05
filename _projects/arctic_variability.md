---
layout: page
title: Oceanic drivers of Arctic climate variability
description: 
img: assets/img/Arctic_simple.png
importance: 1
---
**I worked on this project mainly during Summer 2022 with my mentors Wilbert Weijer, Prajvala Kurtakoti, and Milena Veneziani of the Climate, Oceans, Sea Ice Modeling (COSIM) group at Los Alamos National Lab.**

### A play of air, sea, and ice

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/la_mer.png" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Fragment from Debussy's <i>La Mer</i> (II. "Jeux de vagues", <i>Play of the waves</i>)
</div>

**Arctic climate naturally fluctuates on decade- to multidecade-long timescales**. We know this not only from pre-industrial climate model simulations, but also from observations of sea ice and air temperature going back several hundred years (of course, before the satellite era, observations of sea ice were much more sparse). 

Understanding this variability is important not only for attribution of modern-day Arctic climate change to anthropogenic and natural drivers, but also for gaining process understanding for the mechanisms that drive Arctic climate change. **After all, the Arctic is the region with the most alarmingly rapid rate of climate change.**

**It's difficult to say what exactly drives Arctic decadal variability, in part because the Arctic climate is set by a dynamic interplay between the air, sea, and ice.** 

Past studies ([1](https://www.pnas.org/doi/10.1073/pnas.1422296112), [2](https://link.springer.com/article/10.1007/s00382-009-0569-9)) have used coupled climate models to **show an important role for ocean heat transport**, which enters the Arctic through the Pacific and Atlantic basins. Special attention has been given to the AMOC since it is thought to drive multidecadal variability in the Atlantic basin which may be projected onto the Arctic via ocean heat transport (see [Miles et al.](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2013GL058084) for some cool observational evidence of sea ice and AMV covariability).  

**In this project, we showed that ocean heat transport through the Bering Strait, though much smaller than Atlantic heat transport, plays a surprisingly outsized role in driving decadal Arctic climate variability.** We use an unprecedented 350-year long preindustrial run of a high resolution configuration of CESM. 

We hypothesize that this discrepancy has to do with **compensating effects of atmospheric heat transport** (known as Bjerknes Compensation), which tends to oppose Atlantic heat transport but not so much for Bering Strait heat transport. Additionally, sea ice cover is more sensitive to Bering Strait heat transport, in part because the climatological ice edge is closer to where we evaluate heat transport (65˚N) on the Bering Strait side than on the Atlantic side. Modulation of sea ice then amplifies the Bering Strait heat transport signal through positive radiative feedbacks such as the sea ice-albedo feedback. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/arctic_var_schematic.svg" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    A simplified schematic for different local responses to ocean heat transport
</div>
