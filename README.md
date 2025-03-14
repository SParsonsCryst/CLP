# CLP
Coulomb - London - Pauli CLP-PIXEL: A Computer Program Package for Modelling Intermolecular Interactions

This site makes available the CLP-PIXEL Package written by Angelo Gavezzotti for modelling intermolecular interactions in molecular crystal structures.  We are very grateful to Professor Gavezzotti for making the code available to the community in this way.

CLP-PIXEL is a theoretical approach to the evaluation of intermolecular potential energies, assuming that they can be subdivided into a Coulomb-polarization term, a dispersion term and a Pauli repulsion term.

The CLP approach is implemented in two forms:
>the atom-atom form, AA-CLP: potentials depend on distances between atomic nuclei and are totally empirical. The evaluation of the lattice energy of a crystal structure requires only cell dimensions and atomic nuclear coordinates.

>the PIXEL form: intermolecular energies are calculated as numerical integrals over a large number of electron-density units, or 'pixels'. The method requires one ab initio molecular orbital calculation to prepare the molecular electron density in the form of discrete points on a grid. 

The download contains the programs both as source code (Fortran, in the directory \source) and in compiled form (\exe) suitable for use with Windows.  A manual is provided (\doc) which contains a series of worked examples (\examples).   The CLP-PIXEL programs are called using the batch files (or scripts held in \batch).  

To install the program simply unzip the download into wherever location you wish to store it, though we recommend that no spaces are present in the folder name.  The batch files in \batch will need to be edited to reflect the chosen location unless it is C:\CLP.

The program should be cited as follows:

AA-CLP applied to liquids as well as a description of the method:
Gavezzotti, A. (2011) Efficient computer modeling of organic materials. The atom–atom, Coulomb–London–Pauli (AA-CLP) model for intermolecular electrostatic-polarization, dispersion and repulsion energies. New J. Chem. 35, 1360-1368.
(https://doi.org/10.1039/C0NJ00982B)

Application to crystal structures:
Gavezzotti, A. (2013) Equilibrium structure and dynamics of organic crystals by Monte Carlo simulation: critical assessment of force fields and comparison with static packing analysis. New J. Chem, 37, 2110-2119. (https://doi.org/10.1039/C3NJ00181D)

PIXEL:
Gavezzotti A. (2005) Calculation of lattice energies of organic crystals: the PIXEL integration method in comparison with more traditional methods. Z. Krist. 220, 499-510. (https://doi.org/10.1524/zkri.220.5.499.65063)

A comparison of PIXEL results with a large database of sublimation enthalpies is avilable in:
Chickos, J.S. & Gavezzotti, A. (2019). Sublimation Enthalpies of Organic Compounds: A Very Large Database with a Match to Crystal Structure Determinations and a Comparison with Lattice Energies. Cryst. Growth Des. 19, 6566-6576.
(https://doi.org/10.1021/acs.cgd.9b01006 )

An excellent introduction and discussion of the applications of both methods is available in:
Gavezzotti, A. Molecular aggregation, Structure analysis and molecular simulation of crystals and liquids. Oxford University Press, Oxford 2007; 2nd Edition paperback, 2013.

Further references are provided in the manual.

The use of the CLP computer programs is unrestricted for all users and institutions.

Questions about this download should be addressed in the first instance to Simon Parsons (S.Parsons@ed.ac.uk).  Please note that the program is provided without warranty on an ‘as is’ basis, and it is the user’s responsibility to ensure that it is applied appropriately.  Users should also ensure that they scan for viruses and other malware before installation.
