---
layout: page
title: Numerical Methods for Inverse Games 
description: Inferring the players' motives from their dicision histories in multiplayer games. 
importance: 1
category: work
---

<h2>What is the inverse game problem?</h2>

Inverse games is the problem of inferring players’s motives from their decision histories in noncooperative games. Such an inference explains the behavior of strange decision-makers and, perhaps more importantly, predict their future actions. Solving the inverse game problem can help us predict, for example, whether a basketball player will take a shot when double-teamed, whether a pocker player will call a bluff, how drivers switch their routes when facing unexpected congestion, and how cyberattacks plan their strategies when presented with different honeypots. 

<h2>How do we do it?</h2>

Solving an inverse game problem requires the following four steps. 

- First, we need to mathematical modeling each individual player’s decision-making. In a rock-paper-scissors game, this model is the minimization of a linear function over the probability simplex. In dynamic interactions, this model can either be a linear-quadratic trajectory optimization or a Markov decision process. 

- Second, we need to model how one player’s decisions affect the other players’ decisions. An example of such model is through players’ objective function. For example, in a rock-paper-scissors game, each player minimizes a linear function, whose slope is an affine function of other players’ decisions.

- Third, we need to predict the players’ decisions when they interact with each other. A popular prediction principle is that no player can benefit from an unilateral change of decision, which is commonly known as the <em>Nash equilibrium principle<em>. Other examples of similar principles include the <em>Wardrop equilibrium<em> and the <em>quantal response equilibrium<em>.
  
- Finally, we need to optimize the parameters in our model, typically the players’ objective functions or constraints, such that the decisions predicted by our model match players’ decision history. 

<h2>Why is it interesting NOW?</h2>  

The renewed interests in inverse games come from both practical necessity and theoretical advances. On the one hand, we have autonomous cars driving among human-driven ones, where understanding multiagent interaction is critical. On the other hand, recent results on maximum entropy principle and implicit differentiation allow us to build more powerful differentiable equilibirum models to predict noncooperative decisions. 
  
Inverse games is also the first step of incentive design. Once we have an inference of players' motives, we can provide external incentives to encourage desired behavior. Incentive design has been a central topic in transportation research. It recently gained increasing interests in multiagent robotics.  


<div class="publications">
<h2>Related publications</h2>
{% bibliography -f papers -q @*[invgame=true]* %}
</div>
