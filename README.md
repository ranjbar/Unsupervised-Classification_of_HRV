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

## Results (compiled reports)

The compiled HTML reports, with all tables and figures, can be viewed directly in the browser:

1. [Latent growth mixture model: stress index](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/01_LGM_Stress.html)
2. [Latent growth mixture model: SNS index](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/02_LGM_SNS.html)
3. [Latent growth mixture model: rMSSD](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/03_LGM_rMSSD.html)
4. [Latent growth mixture model: PNS index](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/04_LGM_PNS.html)
5. [Latent growth mixture model: heart rate](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/05_LGM_HR.html)
6. [Latent classes and their determinants](https://ranjbar.github.io/Unsupervised-Classification_of_HRV/html_Results/06_LGM_and_determinants_of_classes.html)

## Data availability

The individual-level data used in this study are accessible on Mendeley Data via [this link](https://data.mendeley.com/datasets/vf73w9hyrx/1).

## Requirements

- R 4.4.1
- Packages: tidySEM (0.2.7), OpenMx (2.21.13), lcmm (2.1.0), flexmix (2.3-19), MASS (7.3-61), dplyr (1.1.4), tidyr (1.3.1), ggplot2 (3.5.2)

## Citation

If you use this code, please cite: [reference].

## License
This code is released under the MIT License. See the LICENSE file for details.
