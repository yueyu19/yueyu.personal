---
layout: page
title: Network Optimization in Transportation
description:  Reducing traffic congestion by designing better infrastructures
importance: 2
category: work
---

Optimizing transportation networks improves the efficiency of traveling from A to B. How can we adjust the tolling price in different lanes to reduce congestion on the road? How can we design the capacity of airports to minimize flight delays under extreme weather conditions? Transportation network optimization answers these questions by analyzing and predicting the behavior of network users and designing incentive mechanisms to mitigate the conflicts of interest among them. 

The optimization of transportation networks is a multidisciplinary matter. We need data analysis and game theory to analyze and model user behavior. We need scalable numerical optimization methods to compute network modification strategies. And we need sensitivity analysis to ensure that our strategies are resilient against imperfect user behavior predictions, network model misspecifications, and unexpected external disturbances.   

<div class="row">
    <div class="col-md-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/manhattan.gif" title="Using Tolling to reduce traffic volume in Manhattan" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Using Tolling to reduce traffic volume in Manhattan.
</div>


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[netopt=true]* %}
</div>
