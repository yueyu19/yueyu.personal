---
layout: page
title: Real-time Trajectory Optimization 
description: Enabling split-second planning in autonomy
importance: 3
category: work
---

Constrained trajectory optimization is critical for autonomy. By optimizing their trajectories subject to physical and operational constraints, we can prevent our autonomous systems--such as drones, rockets, and satellites--from colliding into unexpected obstacles, divert them to a secondary on-the-fly destination when the primary one is compromised, and, in general, improve their adaptivity and resilience.

We develop both theoretically sound and practically efficient solution algorithms for constrained trajectory optimization by exploiting its unique structure. On the theory side, we provide rigorous convergence rate analysis based on Lyapunov analysis for nonlinear and nonsmooth dynamics and infeasibility detection guarantees based on monotone operator theory. On the practical side, we boost the algorithm speed by exploiting the sparsity structure of the problem data and geometric structure of the constraints. 

<div class="row" style="justify-content: center; align-content: center;">
    <div class="col-md-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/landing.pdf" title="Powered descent guidance" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[pipg=true]* %}
</div>
