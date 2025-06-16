# Finite-Element-Method-Analysis-of-a-Mooring-Chain
This project is a Finite element analysis of a steel mooring chain under a constant load using PrePoMax and Gmsh. The geometry is 3 dimensional and consists of a full chain link with two half chain links (Rotated by 90 degrees) on either side. 

the mesh is fully parameterized, which means that you can modify and refine the quality of the mesh just by changing a few parameters listed in the Gmsh code. This makes mesh generation very efficient by eliminating the need for modifying the base code every time. You can access the Gmsh file from this repository and use it for running your own FEA analysis. 

The FEA analysis was performed using PrePoMax, an open-source pre and post processor for the Calculix FEM solver. Since the full chain link and the two half chain links are in contact, a tied contact condition was specified in PrePoMax to obtain the final stress distributions and displacement fields. A mesh independence study was also conducted by refining the mesh and checking for convergence. The analysis showed convergence.
