# ZAD Fission Track Annealing Dataset

**Title**: Thermal Annealing Kinetics of Induced Fission Tracks in ZAD Zircon from the Serra Geral Volcanic Complex, Brazil  
**Authors**: Antonio Said Webbe Sales; Airton Natanael Coelho Dias; Sandro Guedes; Marcela Guinther Medeiros; Vinicius de Queirós Pereira  
**Institution**: Universidade Federal de São Carlos (UFSCar), São Carlos, Brazil  
**Date Released**: 2025-05-28  
**Version**: 1.0.0  
**DOI**: 10.5281/zenodo.15541268  
**License**: CC-BY-4.0

## Description
Comprehensive induced fission track dataset consisting of high-resolution TIFF images and corresponding CSV files containing induced track counts and confined length measurements. Samples underwent pre-annealing at 1100 °C for 1 h, neutron irradiation (1×10¹⁵ n/cm²), followed by thermal annealing at varying temperatures and durations.

## Directory Structure
```
ZAD_Fission_Track_Dataset/
├── README.md
├── CITATION.cff
├── data/
│   ├── raw/
│   │   ├── measurements/
│   │   │   └── TabelaMedicaoZAD.csv
│   │   └── images/
│   │       ├── 1H600/
│   │       ├── 1H700/
│   │       ├── 1H800/
│   │       ├── 10H600/
│   │       ├── 10H700/
│   │       ├── 10H800/
│   │       ├── 100H600/
│   │       ├── 100H700/
│   │       └── 100H800/
├── docs/
│   ├── data_dictionary.md
│   ├── sample_preparation.md
│   ├── methodology.md
│   └── dataset_metadata.json
```

## Samples and Treatments
| t-T     | Temperature (°C) | Duration (h) |
|---------|------------------|--------------|
| 1H600   | 600              | 1            |
| 1H700   | 700              | 1            |
| 1H800   | 800              | 1            |
| 10H600  | 600              | 10           |
| 10H700  | 700              | 10           |
| 10H800  | 800              | 10           |
| 100H600 | 600              | 100          |
| 100H700 | 700              | 100          |
| 100H800 | 800              | 100          |

## Access to Dataset Files

**All dataset files are available for download from Zenodo:** https://doi.org/10.5281/zenodo.15541268

The complete dataset is provided as a single compressed file (ZAD_Fission_Track_Dataset.zip, 8.2 GB) containing all images, measurements, and documentation. After downloading and extracting the ZIP file, you will have access to:

## Contents
- **data_dictionary.md**: Definitions of variables and file descriptions
- **sample_preparation.md**: Detailed sample preparation protocols
- **methodology.md**: Statistical analysis and annealing experiment details
- **dataset_metadata.json**: JSON-LD metadata schema file
- **TabelaMedicaoZAD.csv**: Measurement summary CSV file
- **Image directories**: High-resolution TIFF images organized by treatment conditions (1H600, 1H700, 1H800, 10H600, 10H700, 10H800, 100H600, 100H700, 100H800)

## Keywords
fission track; zircon; thermal annealing; microscopy; induced tracks; CSV; TIFF.

## How to Cite
Sales, A.S.W. Sales; A.N.C. Dias; S. Guedes; M.G. Medeiros; V.Q. Pereira (2025). Thermal Annealing Kinetics of Induced Fission Tracks in ZAD Zircon from the Serra Geral Volcanic Complex, Brazil [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.15541268