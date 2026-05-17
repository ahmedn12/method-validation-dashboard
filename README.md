# Bioanalytical Method Validation Dashboard
**FDA BMV-compliant LC-MS/MS method validation in Python**

## Overview
Python-based automated validation pipeline for a small molecule LC-MS/MS assay 
in human plasma, following FDA Bioanalytical Method Validation Guidance (2018) 
and ICH M10 guidelines.

## Validation Parameters
- Calibration curve (weighted 1/x² regression, 9-point, LLOQ–ULOQ)
- Accuracy & precision (within-run and between-run, 3 runs × 5 replicates)
- LOD & LOQ estimation from calibration residuals
- Matrix effect (IS-normalized, 6 donor lots)
- Dilution integrity (2× and 5×)
- Automated pass/fail report against FDA BMV acceptance criteria

## Tools
Python · pandas · numpy · scipy · matplotlib · plotly

## Author
Nadia Tasnim Ahmed, PhD  
Pharmaceutical Data Scientist | LC-MS · PBPK · CMC
