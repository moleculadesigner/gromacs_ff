# gromacs_ff
Trusted force field files for gromacs in this repo:

- https://github.com/intbio/gromacs_ff/tree/master/amber14sb_parmbsc1.ff from Gromacs web-site
- https://github.com/intbio/gromacs_ff/tree/master/amber14sb_parmbsc1_cufix.ff same but with CUFIX corrections

## General notes on available force fields
### Simulating DNA

### Simulating disordered protein

### Simulations of proteins and protein folding

## Links to external ff resources
### AMBER
- http://ambermd.org/AmberModels.php
- http://ambermd.org/doc12/Amber18.pdf see section 3.
- As of 2018 -  ff14SB is the recommended protein force field in Amber.
- ff14SB paper https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4821407/pdf/nihms772276.pdf
- For DNA one should use currently  PARMBSC1 corrections with AMBER or OL15.
- Ion parameters are important see [section 3.6](http://ambermd.org/doc12/Amber18.pdf). Amber currently recommends Li & Merz parameters (2015).
- [CUFIX corrections](http://bionano.physics.illinois.edu/CUFIX) by Yoo & Aksimentiev, 2018, are important for charged systems
- [OL ff refinements for DNA and RNA](https://fch.upol.cz/ff_ol/index.php)
- [OPC water model](https://bioinformatics.cs.vt.edu/~izadi/)



 
