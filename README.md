# VASP_OpticalP
The optical properties of 2D materials with the VASP code

Due to the enhanced coulomb interaction and the quantum confinement effect in the two-dimensional limit, 
the optical properties should be investigated with the GW+BSE method.

The practical calculation flow is the following :

1.  Perform a ground state DFT or HSE06 hybrid calculation.

2.  Based on previous converged charge density and wavefunction, increasing the number of unoccupied orbitals to generate new charge density and wavefunction. 

3.  Preform a GW calculation (keeping orbitals fixed) and calculate the quasiparticle energies and screened Coulomb kernel. (Keep the Wxxx.tmp and WFULLxxx.tmp files).

4.  Perform BSE calculation (the dielectric function will be written in vasprun.xml)

5.  Plot the results using Sumo or OriginLab

I will soon upload an examples related to the optical properties of two-dimensional materials using DFT and then based on GW+BSE implemented in VASP package.
