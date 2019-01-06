# MOdel BuIlder (MOBI)

MOBI automatically calculates the Lagrangian provided the symmetry group and the particle content of a given model, and it also allows to extract individual interactions of particles. It speeds up the model-building and avoiding errors. 5 theories  based on (products of) abelian and discrete symmetries are given as examples to showcase the performances of the code.

## Log
* 01/08/2015: fixed bug in liExtract, added elegant definition of groups, added model 'radiative inverse seesaw'.  
* 27/07/2015: added liDim to name the couplings of the lagrangian with meanigful symbols. Defined li\[Chi]prod to handle chirality as a symmetry.
* 07/12/2014: fixed misc bugs, added U(1) support, defined Z2 + SU(3), renormailzability check, conjugability. New convention for particles names: fermions must start with F. Conjugate particles are defined with "Conjugate".
* 01/2012: creation. 
