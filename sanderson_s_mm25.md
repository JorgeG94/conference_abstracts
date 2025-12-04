# Local temperature measurement in molecular dynamics simulations with rigid constraints, and implications for numerical integration

## Presenting Author
Stephen Sanderson

## Authors
Stephen Sanderson, Shern R. Tee, Sobin Alosious, Debra J. Searles

## Abstract
Constraining molecules in simulations (e.g. fixed bond lengths or angles) reduces their degrees of freedom (DoF), which affects temperature calculations. When calculating local temperature, e.g. to measure a temperature profile under heat or mass flow, the result can appear to unphysically violate equipartition of the kinetic energy (KE) if the local DoF are not correctly calculated. This talk demonstrates how to correctly calculate such local temperatures. The method is validated on various systems, and shown to provide a sensitive test for the breakdown of KE equipartition caused by the approximate nature of numerical integration or insufficient equilibration times. Interestingly, we find that KE equipartition between C and H atoms connected by rigid bonds can be violated even at the commonly used time step of 2 fs, and that violation usefully indicates configurational overheating. The method is implemented as open source software, and includes a plugin to MDAnalysis for ease of use.
