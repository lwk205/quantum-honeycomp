## QUANTUM HONEYCOMP ##

# Aim #

This program allows to perform tight binding calculations with a user friendly interface


# How to install #

The program runs in Linux and Mac machines. 

Download the file "quantum-honeycomp-latest.tar", uncompress it, and execute the script "install". Afterwards, you can execute the program by writting in a terminal "quantum-honeycomp"

This program uses several Python libraries. The simplest way of getting all the dependencies is by installing Python Anaconda from https://www.anaconda.com/distribution/#download-section 

For using this program in Windows, the easiest solution is to create a virtual machine using Virtual Box, installing
a version of ubuntu in that virtual machine, and following the previous instructions.


# Examples
This program allows to study a variety of electronic states by means of tight binding models as shown below.

## Quantum anomalous Hall state
Honeycomb lattice with Rashba spin-orbit coupling and exchange field, giving rise to a net Chern number and chiral edge states
https://journals.aps.org/prb/abstract/10.1103/PhysRevB.82.161414
![Alt text](screenshots/qah.png?raw=true "QAH state")


## Quantum Spin Hall state
Honeycomb lattice with Kane-Mele spin-orbit coupling and Rashba spin-orbit coupling, giving rise to a gapped spectra with a non-trivial Z2 invariant and helical edge states https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.95.226801
![Alt text](screenshots/qsh.png?raw=true "QSH state")

## Magnetism in graphene zigzag nanoribbons
Self-consistent mean field calculation of a zigzag graphene ribbon, with electronic interactions included as a mean field Hubbard model. Interactions give rise to an edge magnetization in the ribbon, with an antiferromagnetic alignment between edges
![Alt text](screenshots/zzscf.png?raw=true "Magnetism in zigzag nanoribbons")


## Nodal line semimetal
band structure of a slab of a 3D nodal line semimetal in a diamond lattice, showing the emergence of topological zero energy drumhead states in the surface of the slab https://link.springer.com/article/10.1007%2Fs10909-017-1846-3
![Alt text](screenshots/nodalline.png?raw=true "Magnetism in zigzag nanoribbons")


## Confined modes in 0D systems
Spectra and spatially resolved density of states of a triangular graphene island, showing the emergence of confined modes
![Alt text](screenshots/island.png?raw=true "Confined modes in a graphene island")


## Landau levels
Electronic spectra of a massive honeycomb lattice in the presence of an off-plane magnetic field, giving rise to Landau levels and chiral edge states
![Alt text](screenshots/zzqh.png?raw=true "Landau levels in a massive zigzag honeycomb ribbon")

## Twisted bilayer graphene
Bandstructure and local density of states of twisted bilayer graphene at the magic angle, showing the emergence of a flat band, with an associated triangular density of states
https://journals.aps.org/prb/abstract/10.1103/PhysRevB.82.121407
![Alt text](screenshots/tbg.png?raw=true "Magic angle twisted bilayer graphene")

# Capabilities #
- Tight binding models in different lattices (triangular, square, honeycomb, Kagome, Lieb, diamond, pyrochlore)
- Tunable parameters in the Hamiltonian (Fermi energy, magnetic order, sublattice imbalance, magnetic field,  Rashba spin-orbit coupling, intrinsic spin-orbit coupling, Haldane coupling, anti-Haldane coupling, s-wave superconductivity)
- Different results are automatically plotted from the interface
- Band structure of 0d,1d,2d systems
- Density of states of 0d,1d,2d systems
- Selfconsistent mean field Hubbard calculations of 0d,1d,2d systems
- Berry curvature, Chern number and Z2 invariant in 2d systems
- Special module to deal with systems with 100000 atoms using the Kernel polynomial method
- Special modules to study 1d and 2d study interfaces between different systems

