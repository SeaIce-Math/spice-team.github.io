---
title: NYU Davis
layout: default_group
---
# Super-parameterization of Lagrangian sea ice dynamics using the Boltzmann equation 
A. Davis(1), D. Giannakis(1), G. Stadler(1), and S. Stechmann(2)

(1) <i>New York University</i>

(2) <i>University of Wisconsin</i> 

## Abstract
 We devise a superparameterized sea ice (SPICE) model that
captures dynamics at multiple spatial and temporal scales. Arctic sea ice
contains many ice floes---chunks of ice---whose macro-scale behavior is
driven by oceanic/atmospheric currents and floe-floe interaction. There is no
characteristic floe size; data suggest the floe size distribution follows a power
law. Therefore, accurately modeling sea ice dynamics requires a multi-scale
approach. Our two-tiered model couples basin-scale conservation equations
with small-scale discrete element particle methods. The basin-scale sea ice
dynamics are primarily driven by external forces (wind and ocean stresses),
which advect ice floes. Small-scale floe dynamics---deformation, fracture,
and collisions---lead to emergent behavior such as lead formation and
ridging. Unlike many other sea ice models, we do not average quantities of
interest (e.g., mass/momentum) over a representative volume element; we
explicitly model small-scale dynamics. We formulate a mathematical
modeling framework that rigorously couples a macro-scale PDE with small
scale particle methods.

Our framework constructs a time dependent probability distribution over floe
position and velocity. In theory, the particle density function evolves
according to the Boltzmann equation. In practice, numerically solving the
Boltzmann equation is computationally intractable. The SPICE model
decomposes the density function into a mass density that models how ice is
distributed in the spatial domain and a velocity density that models the
small-scale variation in velocity at a given location. We show that the mass
density and macro-scale quantities of interest (e.g., expected velocity)
evolve according to a conservation equation that only depends on the
macro-scale spatial coordinate. However, the flux term depends on
expectations with respect to the velocity density at each point. We,
therefore, use particle methods to simulate the conditional density at key
points, using macro-scale variables to define auxiliary particle forces so that
the small-scale particle methods are independent.

## Presentation
<p><a href="https://drive.google.com/file/d/1nX8cohS7wjcOf85XBgDB2IMKrZ0JoMva/view?usp=sharing">View presentation slides</a></p>


## Video
<iframe src="https://drive.google.com/file/d/1UhmyQlmY_yrtPxMbKrfm3TuWsFeAYGQ4/preview" width="640" height="480"></iframe>
