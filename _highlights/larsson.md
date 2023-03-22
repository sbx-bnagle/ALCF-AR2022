---
layout: highlight

theme: white
permalink: '/science/highlights/larsson'

title: 'Larsson'
pi: 'Name A. Name, Affiliation'
award: 'PROGRAM'
hours: 'Machine and hours'
field: 'field'
sdl: 's,d,l'

image: 'fpo.jpg' 
image-caption: 'The quick brown fox jumps over the lazy dog.'
image-credit: 'Name A. Name, Affiliation'

publications:
  - authors: 'Name A. Name'
    title: 'Pub Title'
    source: 'Pub Source'
    date: 'January 2023'
    publisher: 'Pub Publisher'
    url: 'https://alcf.anl.gov/'
  - authors: 'Name A. Name'
    title: 'Pub Title'
    source: 'Pub Source'
    date: 'January 2023'
    publisher: 'Pub Publisher'
---



{% include txt-intro.html 
    blurb = "High-speed air flows, such as those experienced by supersonic aircraft, create a thin boundary layer along a solid surface. If the boundary layer is hit by a shock wave, as forms when a plane approaches supersonic speeds and pushes on the surrounding air, the flow may separate from the surface. If the flow separates from the surface, the engine’s performance degrades significantly. A team led by researchers from the University of Maryland used ALCF supercomputing resources to study supersonic turbulent boundary layers and their interaction with shock waves."
%}



## Challenge

With the aim of elucidating how shock/boundary-layer interactions (SBLI) are affected by crossflow (that is, flow along the shock and in a direction parallel to the wing span), researchers performed direct numerical simulations of skewed SBLI with crossflow so as to approximate the off-design operating conditions that can ultimately cause engine performance degradation and flameout. 



## Approach

Leveraging the ALCF’s Theta supercomputer, the team carried out SBLI simulations with the code Hybrid. Hybrid is a solver for the compressible Navier-Stokes equations that govern much of fluid dynamics. 



## Results

The team published their results in *Theoretical and Computational Fluid Dynamics* and the *AIAA Journal*. Their papers demonstrate that the size of a turbulent flow’s separation bubble grows almost 50 percent larger in the presence of crossflow than in cases without crossflow.



## Impact

The ultimate goal of the team’s research is to develop a predictive theory for SBLI physics and apply it so as to devise improved modeling techniques for surfaces in large-eddy simulations (LES). LES, as mathematical models for turbulence, are used in a broad range of applications throughout different fields of engineering.

The team expects their findings to help construct improved models that better predict the size of separation bubbles and account for the effect of crossflow for a range of engineering applications. This work is also significant in how it differs from other research in the fields. Historically, most studies of turbulent boundary layers focus on a specific canonical case: the case of incompressible flow, with constant density and viscosity, passing over rigid walls. This research, in contrast, examines the case of compressible flows non-uniform density and viscosity across their boundary layers.
