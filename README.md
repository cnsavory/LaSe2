# LaSe<sub>2</sub>


Repository for paper:  Ab initio Electronic and Optical Properties of Lanathanum Diselenide

DOI: [N/A](N/A)

Optimised crystal structures, vasprun.xml calculation output files, vibrational spectroscopy peak tables and AMSET inputs for LaSe<sub>2</sub> from density functional theory, calculated using the Vienna *Ab initio* Package (VASP).

Computational Details
-----------------------
The crystal structures of P2<sub>1</sub>/c and P4/nmm LaSe<sub>2</sub> obtained by Benazeth et al.<sup>1</sup> and Yarembash et al.<sup>2</sup> were used as the starting point for the calculations.

The final structures have been obtained following an iterative procedure where the ion positions, cell shape, and cell volume are allowed to change (`ISIF = 3` in VASP) using a Quasi-Newton algorithm.

Subsequent electronic structure calculations (DOS, electronic band structure, optics) were performed in VASP, using the settings given in the individual vasprun.xml files. Calculation of vibrational intensities used the [PhonopySpectroscopy](https://github.com/JMSkelton/Phonopy-Spectroscopy) package, while calculation of transport properties uses the [AMSET](https://hackingmaterials.lbl.gov/amset/) package. Due to file sizes, vasprun.xml files are hosted on zenodo.

Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.


References
-------
1. S. Bénazeth, D. Carré, P. Laurelle, Structure du diséléniure de lanthane stoechiométrique LaSe<sub>2</sub>. I. Cristaux maclés suivant la loi (100): forme B, *Acta. Cryst. B*, **38**, 33-37 (1982) doi: [10.1107/s0567740882001988](https://scripts.iucr.org/cgi-bin/paper?S0567740882001988)
2. E. I. Yarembash, E. S. Vigileva, R. R. Kagramanova and L. K. Kravchen-Ko, Phase Diagram of the La-Se system, *Inorg. Mater.*, **5**, 217-220 (1969) 
