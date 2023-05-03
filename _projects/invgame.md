---
layout: page
title: Algorithmic Inverse Games
description:  Inferring What Games You Are Playing 
importance: 1
category: work
---


Inverse games are about inferring players’ motives from their interaction history. What motivates a basketball player to make tough shots when double-teamed, or a poker player to call a bluff? Inverse games answer these questions by explaining the players’ past decisions, and help predict the players’ future actions. 

Inverse games include two steps: mathematical modeling players’ interactions and numerically optimizing model parameters. In the first step, we develop game theoretical models to explain and predict players’ interactions by combining ideas from control theory, and decision science. In the second step, we develop numerical optimization and statistical learning methods to compute parameters that optimally explain observed interaction history.   

Inverse games are also the foundation of incentive design. If we can infer what motivates the players’ decisions, we can infer the incentives that encourage desirable player behavior. For example, by adding incentives, we can motivate robots to choose collision-free paths even though they cost more battery. 


<p align = "center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/EvtPp_DWqgU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>  


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[invgame=true]* %}
</div>
