# KCROOZ
Repository of optimized zeolite lattice constants using the PBE functional. 

# Purpose
The purpose of this repository is to provide zeolite structures with optimized lattice constants found using a uniform method. The first step in any computational zeoltie research is to optimize the lattice constants for the structure. We hope to save time for other researchers who intend to use these zeolite structures by removing that first step. 

# Source
All initial structures are taken from the [http://www.iza-structure.org/databases/][IZA Database of Zeolite Structures]. 

# Optimization
All structures are optimized using the Vienna \italics{ab-initio} Simulation Package (VASP). An example INCAR is available to clarrify inputs used for each simulation. Supercell shape and size are allowed to change, and the calculations continue until the energy change between iterations is less than 1E-6 eV. 

# Future 
More zeolite structures will regularly be added. It is possible that different functionals will used if there is a demand. 
