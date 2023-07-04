---
layout: page
title: Algorithmic Inverse Games
description:  What games are you playing? 
importance: 1
category: work
---


Inverse games are about inferring players’ motives from their interaction history. What motivates a basketball player to make tough shots when double-teamed, or a poker player to call a bluff? Inverse games answer these questions by explaining the players’ past decisions and help predict the players’ future actions. 

Inverse games include two steps: mathematical modeling of players’ interactions and numerically optimizing model parameters. In the first step, we develop game theoretical models to explain and predict players’ interactions by combining ideas from control theory, and decision science. In the second step, we develop numerical optimization and statistical learning methods to compute parameters that optimally explain observed interaction history.   

Inverse games are also the foundation of incentive design. If we can infer what motivates the players’ decisions, we can infer the incentives that encourage desirable player behavior. For example, by adding incentives, we can motivate robots to choose collision-free paths even though they cost more battery. 


<div class="row" style="justify-content: center; align-content: center;">
    <div class="col-md-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/incentive.gif" title="Incentive design in multi-rover path planning" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- <div class="caption">
    Incentivizing collision-avoidance in multi-rover path planning.
</div>
 -->


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[invgame=true]* %}
</div>
