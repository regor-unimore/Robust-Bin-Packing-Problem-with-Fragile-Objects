# Robust-Bin-Packing-Problem-with-Fragile-Objects

This folder contains all the instances used in the manuscript: "Mathematical Formulations for the Robust Bin Packing Problem with Fragile Objects" by Heloisa Vasques da Silva, Alberto Locatelli, Silvio Alexandre de Araujo, and Manuel Iori, 2024.

## Instance Details

The instances were generated according to the Section 5.1 of the manuscript. They are organized in the folder "InstancesRBPPFO". The file names follow the pattern: "{N}{C}{W}_{CL}_{inst}_{U}.txt", meaning:

N: Number of items (N1 = 50, N2 = 100);
C: Capacity (C1, C2, C3) used in the BPPFO instances created by Clautiaux et al. (2014)*; 
W: Weight intervals (W1 = [1, 100], W2 = [20, 100], W4 = [30, 100]);
CL: Fragility class:
  - CL1_1_3 = Class 1,
  - CL1_1_5 = Class 2,
  - CL2_1_5 = Class 3,
  - CL2_3_3 = Class 4,
  - CL2_3_4 = Class 5.
I: Instance identifier (A, B, C, D, E);
U: Uncertainty level (3L indicating low level of uncertainty).

## Input File Format

Each input file contains:

- First line: The number of items (N).
- Subsequent lines: Given an item j in {1,...,N}, lines 3+j specifies the weight, the deviation and the fragility, separated by a blank space.


## References

*Clautiaux, F., Dell Amico, M., Iori, M., Khanafer, A.: Lower and upper bounds for the bin packing problem with fragile objects. Discrete Applied Mathematics 163, 73–86 (2014);
