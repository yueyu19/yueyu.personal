---
layout: page
title: Inverse Learning for Multiplayer Games 
description: Inferring the players' motives from their dicision histories in multiagent interaction 
importance: 1
category: work
---

<h2>What is the inverse game problem?</h2>

Inverse games is the problem of inferring players’s motives from their decision histories in noncooperative games. Such an inference explains the behavior of strange decision-makers and, perhaps more importantly, predict their future actions. Solving the inverse game problem can help us predict, for example, whether a basketball player will take a shot when double-teamed, whether a pocker player will call a bluff, how drivers switch their routes when facing unexpected congestion, and how cyberattacks plan their strategies when presented with different honeypots. 

<h2>How do we do it?</h2>

Solving an inverse game problem requires the following three steps. First, we need to mathematical modeling each individual player’s decision-making. In a rock-paper-scissors game, this model is the minimization of a linear function over the probability simplex. In dynamic interactions, this model can either be a linear-quadratic trajectory optimization or a Markov decision process. Second, we need to model the coupling among different players’ decisions via a parameterized objective functions or constraints. Such coupling determines how one player’s decisions affect the others’. Finally, we must optimize the parameters in the players’ objective functions or constraints such that the players’ decisions in a Nash equilibrium—or other notions of equilibrium—matches the players decision histories.


<h2>What are the applications?</h2>


<div class="publications">
<h2>Related publications</h2>
{% bibliography -f papers -q @*[invgame=true]* %}
</div>
