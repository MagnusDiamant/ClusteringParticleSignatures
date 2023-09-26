# ClusteringParticleSignatures
The project concerns classification, regression, and unsupervised learning (i.e. clustering) on structured data sets of simulated proton collisions. 


## The Data
The data consist of 162500/160650 (train/test) simulated particle collisions and interactions in the ATLAS detector, situated at CERN's LHC accelerator ourside Geneva. Colliding protons, one is interested in collisions, which produce e.g. electrons (as thus new particles decaying to electrons must have been produced, since there are no electrons inside protons). Electrons interact in a particular way in the detector, leaving a distinct signature different signature than other particles. Each candidate in the file is described by 166 variables.
As the data is simulated, the "ground truth" is known, and we thus have perfect labels (for both particle type and energy), which we can use for the supervised training.



## Problem Statement:
One would like to identify the electrons in the best possible way (i.e. separate them from other particles) and also determine their energy as accurately as possible. Finally, one would generally like to distinguish different particle signatures as well as can be done, unsupervised. 
The goal is to identify (i.e. classify) electrons vs. non-electrons, estimate (i.e. make regression for) the energy of electrons and cluster particle signatures into 3+ catagories. 
