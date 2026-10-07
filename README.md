# Unsupervised Classification of HRV

Code to reproduce the results in the manuscript *"Unsupervised classification of heart-rate variability in the general male population"* [authors, journal, year, DOI].

## Contents

The repository contains six R Markdown files, which should be run in the order given by their numeric prefix:

1. `01_LGM_Stress.Rmd`: latent growth mixture model for the stress index
2. `02_LGM_SNS.Rmd`: latent growth mixture model for the SNS index
3. `03_LGM_rMSSD.Rmd`: latent growth mixture model for rMSSD
4. `04_LGM_PNS.Rmd`: latent growth mixture model for the PNS index
5. `05_LGM_HR.Rmd`: latent growth mixture model for heart rate
6. `06_LGM_and_determinants_of_classes.Rmd`: combines the class assignments and analyses their determinants

## Data availability

The individual-level data used in this study are not included in this repository because of [participant confidentiality / cohort data-access policy]. Researchers can request access from [cohort/institution, contact or URL].

## Requirements

- R 4.4.1
- Packages: tidySEM (0.2.7), OpenMx (2.21.13), lcmm (2.1.0), flexmix (2.3-19), MASS (7.3-61), dplyr (1.1.4), tidyr (1.3.1), ggplot2 (3.5.2)

## Citation

If you use this code, please cite: [reference].

## License
This code is released under the MIT License. See the LICENSE file for details.
