Data, config files and analysis notebooks used for our recent paper titled "Oxygen Isotope Ratios in Hydrogen-Deficient Carbon Stars: A Correlation with Effective Temperature and Implications for White Dwarf Merger Outcomes". 

This work was done using a modified version of TSFitPy, which is available [here](https://github.com/advaitmehla/TSFitPy). Below is a description of the files that can be found here:
- The `data/` directory stores reduced, continuum-subtracted, high-resolution K-band spectra of 9 RCB and 6 dLHdC stars acquired using the iShell instrument at IRTF in late 2022.
- The `input_files/` directory contains config files for the various fitting steps used for obtaining abundances and oxygen isotope ratios for each star, along with the linemasks (`/hdc_model_atmospheres`), and the custom HdC MARCS models used in our work (located in `/hdc_model_atmospheres`)
- The `analysis/` directory contains Jupyter notebooks used for analyzing the fits obtained for each star, along with notebooks used to generate the plots used in our paper.

If you have any questions regarding our work or need help with using our code for your own work, feel free to contact me at [advaitmehla@iitb.ac.in](mailto:advaitmehla@iitb.ac.in).
