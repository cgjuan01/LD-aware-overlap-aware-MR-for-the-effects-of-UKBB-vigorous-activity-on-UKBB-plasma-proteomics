This repository contains an end-to-end R pipeline implementing LD-aware and sample-overlap–corrected Mendelian randomisation (MR) to estimate the causal effects of UK Biobank (UKBB) accelerometer-derived vigorous physical activity on UKBB Pharma Proteomics Project (PPP) plasma protein levels.

The workflow integrates:

Fine-mapped vigorous-activity SNPs (exposure)

UK Biobank Pharma Proteomics Project v1 & v2 protein GWAS (outcomes)

Generation Scotland LD reference panel (87×87 LD matrix)

Overlap-aware IVW estimator, adjusting for exposure–outcome sample overlap via rho

Full SNP harmonisation, allele alignment, LD re-ordering, and robust error handling

This pipeline is designed for large-scale, automated MR screens across thousands of proteins.
