# Data and analysis scripts for ***Secondary structure of the SARS-CoV-2 genome is predictive of nucleotide substitution frequency***

Related to the manuscript: *Secondary structure of the SARS-CoV-2 genome is predictive of nucleotide substitution frequency* (**PUT bioRxiv DOI here**)

## File descriptions

* `/data/dms-reactivity/ `
  Supplementary Data 8 from Lan et al 2022 ([DOI: 10.1038/s41467-022-28603-2](https://doi.org/10.1038/s41467-022-28603-2)). Description by authors: *Population average DMS reactivities for the datasets from Huh7 cells (filtered) and Vero cells (filtered), as well as from each replicate in Vero cells (unfiltered).* Published under the terms of the Creative Commons Attribution License ([https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)).
* `/data/mut-fitness/ `
  Nucleotide-level mutational fitness estimates from Bloom & Neher 2023 ([DOI: 10.1093/ve/vead055](https://academic.oup.com/ve/article/9/2/vead055/7265011?login=false#417534142:~:text=https%3A//doi.org/10.1093/ve/vead055)). Specifically, files [nt_fitness.csv](https://raw.githubusercontent.com/jbloomlab/SARS2-mut-fitness/7930c72fee719f9425a7a30eb8da10436c2da930/results/nt_fitness/nt_fitness.csv) and [ntmut_fitness_all.csv](https://raw.githubusercontent.com/jbloomlab/SARS2-mut-fitness/7930c72fee719f9425a7a30eb8da10436c2da930/results/nt_fitness/ntmut_fitness_all.csv) (URLs point to the GitHub commit used in my analysis). Published under the terms of the [MIT License](https://github.com/jbloomlab/SARS2-mut-fitness/blob/main/LICENSE.md).
* `/data/sars2-secondary-structure/ `
  Supplementary Data 6 and 7 from Lan et al 2022 ([DOI: 10.1038/s41467-022-28603-2](https://doi.org/10.1038/s41467-022-28603-2)). Descriptions by authors: *Genome-wide secondary structure model of SARS-CoV-2 base on DMS reactivities in [Vero/Huh7] cells, in connectivity table (CT) format*. Published under the terms of the Creative Commons Attribution License ([https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)).
* `/figures/ `
  Figures included in manuscript in PNG and SVG formats.
* `/notebooks/ `
  Jupyter notebook (Python 3.12.1) utilized for all analysis and figure generation reported in the manuscript except for manual inspection of frequencies of mutations in major lineages at [covSPECTRUM](https://cov-spectrum.org/).
