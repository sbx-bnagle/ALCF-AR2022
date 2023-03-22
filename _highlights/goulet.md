---
layout: highlight

theme: white
permalink: '/science/highlights/goulet'

title: 'Joshua-New'
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
    blurb = "Ground motions and fault displacements from earthquakes threaten infrastructure. Computer-based simulations can provide insight on those earthquake hazards to help develop mitigation strategies. Led by researchers from the Southern California Earthquake Center (SCEC), this INCITE project seeks to improve earthquake-modeling capabilities by integrating physics-based models into research software, validating ground motion simulation and hazard products, while improve code performance."
%}



## Challenge

Civil infrastructure is at risk of damage due to earthquake ground motions and fault displacement. In areas close to the fault (within 10-20 km), empirical models for both hazards are poorly constrained due to the paucity of data. This INCITE project is using DOE supercomputing resources to simulate ground motion and displacement using dynamic rupture codes that include complex physics to produce high-frequency simulations. The results are cross-validated with existing empirical data and used to extrapolate earthquake effects where no data exist. The researchers are looking to improve the accuracy of rupture simulations by adding features such as complex fault geometry and nonlinearity in the geological models.  



## Approach

The team’s work at the ALCF is largely driven by two open source codes, Waveqlab3D and SORD, which are used to simulate earthquake rupture dynamics and seismic wave propagation. The researchers are using Theta to look at fault displacement from dynamic rupture simulations for earthquakes with a magnitude greater than seven with different initial conditions. They are also generating broadband dynamic rupture sources with off-fault plasticity and geometrical fault complexity. With this work, the team is creating a database of slip-strike earthquake mechanisms, comparing broadband ground motions with empirical trends predicted by empirical ground motion models. They also are modeling ruptures across dipping faults, which have unique geometrical complexities. ALCF staff helped with scheduling jobs, and compiling and running SORD with Cray MPI.



## Results

In one study, the INCITE team used Theta to simulate the 1992 Landers, CA earthquake by defining a preferred model that reproduced first-order fault displacement metrics including the on-fault partition of the total displacement. This has demonstrated that all the physics important to modeling the earthquake were properly captured, showing that dynamic rupture modeling can be used to assess fault-displacement hazard on a larger scale. The model reproduced intermediate and large-scale features including displacement, off-fault deformation, fault zone width and peak displacement.



## Impact

Physics-based dynamic rupture models and simulations inform earthquake hazard analyses and assessments, which help prepare for earthquakes and enable mitigation strategies that can save lives and alleviate the societal and economic damage caused by earthquakes.
