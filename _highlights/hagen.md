---
layout: highlight

theme: white
permalink: '/science/highlights/hagen'

title: 'Chang'
pi: 'Name A. Name, Affiliation'
award: 'PROGRAM'
hours: 'Machine and hours'
field: 'field'
sdl: 's,d,l'

image: 'fpo.jpg' 
image-caption: 'The quick brown fox jumps over the lazy dog.'
image-credit: 'Name A. Name, Affiliation'

publications:
  - authors: 'TEst TEst'
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
    blurb = "Protons and atomic nuclei account for 99 percent of the visible mass in the universe, but how protons join together through astrophysical processes to form atomic nuclei is not well understood—nor are the resultant properties of those nuclei. This project, led by researchers from Oak Ridge National Laboratory, focuses on first-principles approaches to nuclear structure and reactions that apply interactions derived within effective theories of quantum chromodynamics (QCD). The calculations performed will make predictions for and guide new experiments at major DOE facilities, explain observed phenomena, and potentially propel the discovery of new laws of nature."
%}



## Challenge

Among the principal tasks of computational nuclear physics is the establishment of a reliable quantitative first-principles description of nuclear structure and reactions. It is presently believed that the most promising approach to achieve this goal combines chiral effective field theory (EFT) (for the description of nuclear reactions in concert with QCD symmetries and breaking patterns), with ab-initio few-body methods (for tackling the quantum-mechanical A-body problem). To address this challenge, the Low Energy Nuclear Physics International Collaboration (LENPIC) aims to develop a precise, accurate description of two- and three-nucleon interactions by pushing the EFT expansion to high-chiral orders and using these interactions to solve the structure and reactions of light nuclei.



## Approach

To perform calculations, the team used the no-core configuration interaction (NCCI) approach implemented in their Many Fermion Dynamics—nuclear (MFDn) code. For the largest runs they used almost the entire Theta machine in quad-flat mode, which gave the best performance and maximal memory, and allowed them to calculate properties of ground and excited states of light nuclei with robust theoretical error estimates.



## Results

The team performed the first tests of novel chiral nucleon-nucleon potentials with consistent three-nucleon interactions. This demonstrates the importance of three-nucleon interactions and allows for a quantitative understanding of the theoretical uncertainties due to the chiral EFT expansion. The team also extended and tested a Bayesian statistical model that learns from the order-by-order EFT convergence pattern to account for correlated excitations. This enabled demonstrated agreement with experimental ground state energies as well as excitation energies. The results were compared to known experimental results to test consistent LENPIC chiral EFT interactions consisting of two- and three-nucleon interactions. The calculated results were consistent with the experimental results, confirming the validity of the approach.



## Impact

Establishing predictive power for nuclear physics carries ramifications for a wide range of fields, including astrophysics, medicine, nuclear power, and nuclear security.
