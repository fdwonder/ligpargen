# LigParGen

## What is LigParGen?

LigParGen is a webbased service that provides force field \(FF\) parameters for organic molecules or ligands, offered by Jorgensen group.

LigParGen provides OPLS-AA force field parameters for modeling bonds, angles, torsions and Lennard-Jones interactions, and uses 1.14\*CM1A charges for modeling electrostatic interactions

LigParGen can deal with molecules as big as Linezoloid shown in Figure 1.
![](linezo.png)

One can obtain topology and parmeter files from SMILES code or by uploading mol\/pdb files of the ligand.

**Supported input file formats: SMILES\(2D\), PDB and MOL \(3D\)**

LigParGen provides the following files upon successfull submission of ligand.

| Package | Parameters | Topology\/Coordinates |
| --- | --- | --- |
| OpenMM | .xml | .pdb |
| CHARMM | .prm | .rtf |
| GROMACS | .itp | .gro |

### References

1. [Potential energy functions for atomic-level simulations of water and organic and biomolecular systems.  Jorgensen, W. L.; Tirado-Rives, J. Proc. Nat. Acad. Sci. USA 2005, 102, 6665-6670. doi:10.1073\/pnas.0408037102.](http://www.pnas.org/content/102/19/6665)
2. If you use our server in your research, please cite us: zarbi.yale.edu\/liggenpar \(paper in preparation\)

## How to use these parameter and topology files?

Files obtained from LigParGen server are useful for performing MD simulations. These files are compatible with MD software such as NAMD, AMBER, GROMACS and OpenMM.

Click on the below links to learn more about installing these packages.

* [GROMACS](http://www.gromacs.org/Documentation/Installation_Instructions_5.0) \(Free\)
* [NAMD](http://www.ks.uiuc.edu/Research/namd/2.10/ug/node93.html) \(Free\)
* [OpenMM](http://docs.openmm.org/6.2.0/userguide/application.html#installing-openmm) \(Free\)

Examples for using these files with different packages will be discussed in this tutorial.

