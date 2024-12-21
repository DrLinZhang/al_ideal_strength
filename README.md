# Stability criteria of Aluminum lattice from first-principles

## Dataset file
[LinearStrengthLateralStressAluminumData.csv](LinearStrengthLateralStressAluminumData.csv)

## Description: 
This dataset contains numerical values of key geometric and physical parameters from a high-throughput ab initio study that investigates the linear relationship of ideal strength with lateral stress under 0-600 GPa of aluminum (Al) lattice, authored by Lin Zhang, Tianle Wang, and Feng Liu. 
The dataset for this computational investigation is extensive, comprising over 69,000 unique structural configurations of Al. 

## Dataset Overview
- a(Å): Unit cell length along the a-axis in Angstroms.
- c(Å): Unit cell length along the c-axis in Angstroms.
- F1: First component of the deformation gradient corresponding to unit cell length 'a'.
- F3: Third component of the deformation gradient corresponding to unit cell length 'c'.
- E1: Lagrangian strain component associated with length 'a'.
- E3: Lagrangian strain component associated with length 'c'.
- Sigma1(GPa): Cauchy stress along the 'a' axis in GigaPascals.
- Sigma3(GPa): Cauchy stress along the 'c' axis in GigaPascals.
- ΔE(ev): Relative energy change compared to a reference state in electron volts.

## Use Guidance
- Format Provided: The data is provided in CSV format, suitable for analyses with various software tools including Python (with libraries like Pandas), MATLAB, R, or for visualization in Excel, etc.
- Typical Analysis: Sample analysis can include constructing scatter plots of deformation gradient components against unit cell lengths as well as Lagrangian strain components. These may provide insights into the material behavior under different stress conditions.

## Paper info and Cite
- Paper Title: Stability criteria of Aluminum lattice from first-principles
- Authors: Lin Zhang, Tianle Wang, and Feng Liu. 
- Journal: Journal of Materials Research and Technology
- Year: 2015
- Volume: 34
- Pages: 1144-1157
- Link: https://www.sciencedirect.com/science/article/pii/S2238785424028953
- DOI: https://doi.org/10.1016/j.jmrt.2024.12.092
- Citation: Please cite our work when using this dataset in your publication or research with the [bib file](S2238785424028953.bib).

## Contributors: 
- Lin Zhang
- Tianle Wang
- Feng Liu

## License
- This dataset is for non-commercial use and subject to an academic license.

## Note
Ensure to acknowledge the source (authors and paper title) and usage rights while exploiting or redistributing this dataset. 
Data sharing norms for this study suggest citing the dataset as a resource in any resulting publications.

## Current Version Note: 
This README serves as a preliminary document and all elements are subject to change until the manuscript reaches peer-reviewed status. 
For precise details on data interpretation, consult the final paper. 
Until the official publication, any results or conclusions drawn from this dataset should be regarded with consideration for potential updates or corrections.
