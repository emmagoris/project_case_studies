This code should allow people to re-run our analysis we conducted for a project for the course Case Studies in Experimental Psychology.

For this project we investigated whether cognitive control tasks activate the cognitive control network similarly, or whether there are task specific activations present. 
To this end we used the available dataset of Braver et al., 2021 on https://openneuro.org/datasets/ds003465/versions/1.0.6
This dataset includes the preprocessed bold-images for 55 participants on four cognitive control tasks. 

To replicate our analysis following steps should be followed: 

1st level analysis of fMRI bold images was conducted in MATLAB version 2023.a (SPM 12 should be downloaded and installed; cf. https://www.fil.ion.ucl.ac.uk/spm/software/spm12/)

- (1) run the code of "1stLevelAnalysis" in this repository
- (2) look at the file of "extraction t-values"


2nd level analysis of the extracted t-values were analysed in R Studio (v. 2022.07.2). The full script of these analyses can be found in the '2ndLevelAnalysis' file. 
- (1) Prior to running the code, the following packages should be loaded in the directory:
ggplot2, dplyr, stringr, lme4, stats, optimx, car, tidyr, lattice, pwr, and readxl
- (2) run the code of the 2ndLevelAnalysis file
- (3) Model results can be observed in the console, and figures will be plot.
