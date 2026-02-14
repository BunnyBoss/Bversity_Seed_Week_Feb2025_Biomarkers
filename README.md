# Genomic Precision Cancer Care

## Project Overview

This repository contains data from a Bversity 2-day workshop conducted on February 10-11, 2025, focusing on biomarker discovery and analysis. The `Day2` and `Day3` folders contain sample patient genomic data in the form of VCF files and annotated VCF files from the Variant Effect Predictor (VEP). The `Documents` folder contains presentations in PDF format and a sample report for the TNBC01 patient from Day 1. The `VCF2BM.ipynb` notebook can be used as a template to prioritize and analyze the variants from VEP output.

## Repository Structure

```
.
├── Day2
│   └── TNBC01
│       └── Inputs
│           ├── IntOGen-DriverGenes_BRCA.tsv
│           ├── TNBC01.VEP.output.txt
│           └── TNBC01.VEP.output.vcf
├── Day3
│   ├── Patient1
│   │   └── Inputs
│   │       ├── SIDM00136.vcf
│   │       └── SIDM00136.vep.output.txt
│   ├── Patient2
│   │   └── Inputs
│   │       ├── SIDM01067.ds.vcf
│   │       └── SIDM01067.ds.vep.output.txt
│   └── Patient3
│       └── Inputs
│           ├── SIDM00138.ds.vcf
│           └── SIDM00138.ds.vep.output.txt
├── Documents
│   ├── Bversity_Biomarker_Discovery_and_Precision_Cancer_Care.pdf
│   └── Genomic_Precision_for_Triple_Negative_Breast_Cancer.pdf
└── VCF2BM.ipynb
```

## Data Description

- **VCF Files**: Variant Call Format files containing genomic variants for each patient.
- **VEP Output Files**: Variant Effect Predictor output files providing functional annotation of genomic variants.
- **TSV File**: Tab-separated values file containing driver genes for breast cancer from IntOGen.
- **PDF Documents**: Research papers and documents related to biomarker discovery and precision cancer care.

## Usage

The data in this repository can be used for various genomic analyses, such as:

- Identifying potential driver mutations in cancer patients
- Investigating the functional impact of genomic variants
- Exploring biomarkers for precision cancer care, including mutations and Tumor Mutational Burden (TMB).

## Contributing

Contributions to this repository are welcome. Please follow these guidelines:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and commit them with descriptive commit messages.
3. Push your changes to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.