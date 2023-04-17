---
layout: page
title: Inverse Learning for Dynamic Games 
description: Inferring the players' motivation from observed dicision history in multiplayer games 
importance: 1
category: work
---


<h2>Robust Analysis of Fault Trees</h2>


<div class="row" style="justify-content: center;">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/sampling_faulttree.png" title="Railway cabinets fault tree" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fault tree for a railway cabinet presented in  Ruijters et al. (2019, Reliab. Eng. Syst. Saf.).
</div>

With our methods, we can analyze the fault tree while being robust against the uncertainty in the failure rates. Concretely, we find prediction regions as in the figures below, which contain the failure probabilities over time with at least a specific (high) probability. Based on these regions, we can determine time-based maintenance policies that are robust against deviations in the failure rates.

<div class="row" style="justify-content: center;">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/sampling_curves.png" title="Prediction regions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: the prediction regions for the case with no inspections; right: the prediction regions with inspections. With our approach, maintenance planners can make decisions about maintenance policies, while taking into account the uncertainty about failure rates of components.
</div>


<div class="publications">
<h2>Related publications</h2>
{% bibliography -f papers -q @*[sampling=true]* %}
</div>
