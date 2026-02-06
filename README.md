# Molecular basis of target RNA cleavage by Cas13   
"[Paper Title](https://doi.org/xxxxxx)"  
Authors · Journal/Preprint · Year

## Abstract
RNA-targeting CRISPR-Cas13 enzymes are robust RNA knockdown tools with both on-target and collateral cleavage activities. However, to date, the in vivo RNA cleavage mechanisms remain poorly understood. Here, we combine in vitro and in vivo methods to elucidate the exact cleavage sites of Cas13. We reveal that some subtypes of Cas13, including Cas13b and Cas13bt, cleave the target RNA at predominant positions, and rational engineering of Cas13 further improves precision. Building on these findings, we develop RNA segment editing (RSE), a targeted RNA cleavage and repair method, to restore dysfunctional RNA in cells. We anticipate that RSE will enable precision RNA engineering for therapeutics and basic research.

## Overview
This repository contains the Snakemake files and Jupyter notebooks used for:
- Processing raw data from NGS
- Generating the main and supplementary figures shown in the paper

All results in the paper can be reproduced with the provided scripts and raw data (available in GEO: xxxxxxx).

## Details
To process and analyze the raw data for **Figure 2 and Supplementary Figures 3-6**, use the snakemake files and Jupyter notebooks located in the scripts folder

- To process the Dictionary samples, use Snakefile_in_vitro_random_dictionary
- To process the Cas13-cleaved samples, use Snakefile_in_vitro_random_cleavage
- To perform statistical analysis and generate the figures, use 260129_JOE_invitro_scatter_rev5.ipynb

To process and analyze the raw data for **Figure 3-5 and Supplementary Figures 8, 10 and 11**, use the snakemake files and Jupyter notebooks located in the scripts folder

- To process the NGS data, use Snakefile_kwon_novaseq
- To visualize the cleavage sites and generate the figures, use 260130_in_vivo_cleavage_site.ipynb

