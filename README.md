# mouse-estg

## eSTG script for sparse simulation of mouse development

This is an eSTG script simulating the third challenge for Allen Institute Cell Lineage Reconstruction DREAM Challenge

## Quick start - Running with eSTGt
Download latest version from Github: https://github.com/shapirolab/eSTGt and copy the files into a separate folder. There are two folders:

1)	eSTGt - includes the source code
2)	Programs - includes program examples

For ease of use add the eSTGt folder into your MATLAB’s path.

![alt text](https://github.com/ofirr/mouse-estg/blob/main/GUI.png?raw=true)

Note that this version simplifies the mutation simulation to integrate with eSTGt. 
For further details see eSTGt manual.

## eSTGt - A programming and simulation environment for population dynamics
eSTGt is a MATLAB tool that enables to execute stochastic simulations that generate lineage trees. The input programs of the tool are based on a language formalism called environmental dependent Stochastic Tree Grammars (eSTG) that is described in a [published paper](https://doi.org/10.1186/1471-2105-15-249). Briefly, the formalism extends the notion of Stochastic Tree Grammars (STG)2 by incorporating both rates and probabilities to the transition rules. These can be dynamically updated by defining them as functions of the system’s state, which includes global values such as current population size or elapsed time. In addition, we extend the system by allowing each individual to hold its own internal states, which can be inherited. The species fate can also be controlled through conditional transitions on the system’s state.

## Advance usage - Running with clineage-simulation
For advanced usage such as HPC execution and advanced mutational mechanism see https://github.com/ofirr/clineage-simulation and follow the repository guidelines
Be sure to use the DREAM branch of this repository or the provided example-dream folder under examples in the clineage-simulation repo.