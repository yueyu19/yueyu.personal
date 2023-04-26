---
layout: page
title: Algorithmic Inverse Games
description: Figuring out what games you are playing 
importance: 1
category: work
---


Inverse games is about inferring players’ motives from their interaction history. What motivates a basketball player’s to make tough shots when double-teamed, or a poker player to call a bluff? How can we infer these motives from what they did in the past? Inverse games answer these questions—and many others—by mathematically modeling players’ interactions and numerically compute the model parameters that give the best explanations for players’ interaction history.

Inverse games is also the foundation of incentive design. If we can infer what motivates the players’ current decisions, we can infer what future incentive or tax mechanisms will keep them in line. For example, by adding proper incentives, we can motivate rovers to choose collision-free maneuvers even though they cost more battery. 


<p align = "center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/EvtPp_DWqgU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>  


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[invgame=true]* %}
</div>
