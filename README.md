
# Catalogue: py4radiation Datasets

This repository provides ready-to-use datasets generated with [py4radiation](https://github.com/cPhysPlus/py4radiation), including:

- **Heating and cooling functions in ASCII format:** these can be readily coupled to any existing hydrodynamic code, like [PLUTO/gPLUTO](https://plutocode.ph.unito.it).
- **Ion fraction tables in HDF5 format:** these can be readily coupled to post-processing tools, like [Trident](https://github.com/trident-project/trident).

## Data Description

### 1. Tabulated Heating and Cooling Functions

The datasets are organised into three groups, each containing two files at different resolutions.

| Radiation Field | Format | Resolution ($n_{\rm H},T$) | File size | Download |
|:----------------|:------:|:----------------------------:|:---------:|:--------:|
| meta-galactic   | ASCII | Low (27, 81) | 0.15 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/hm2012_cooltable_lr.dat) |
| meta-galactic   | ASCII | High (105, 321) | 2.38 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/hm2012_cooltable_hr.dat) |
| starburst-5kpc  | ASCII | Low (27, 81) | 0.15 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb5kpc_cooltable_lr.dat) |
| starburst-5kpc  | ASCII | High (105, 321) | 2.38 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb5kpc_cooltable_hr.dat) |
| starburst-1kpc  | ASCII | Low (27, 81) | 0.15 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb1kpc_cooltable_lr.dat) |
| starburst-1kpc  | ASCII | High (105, 321) | 2.38 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb1kpc_cooltable_hr.dat) |

### 2. Tabulated Ion Fraction Tables

Ion fraction tables are provided in HDF5 format for the same three radiation fields and two resolutions.

| Radiation Field | Format | Resolution ($n_{\rm H},T,z$) | File size | Download |
|:----------------|:------:|:----------------------------:|:---------:|:--------:|
| meta-galactic   | HDF5 | Low (27,81,2) | 16.58 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/hm2012_iontable_lr.h5) |
| meta-galactic   | HDF5 | High (105,321,2) | 254.72 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/hm2012_iontable_hr.h5) |
| starburst-5kpc  | HDF5 | Low (27,81,2) | 16.58 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb5kpc_iontable_lr.h5) |
| starburst-5kpc  | HDF5 | High (105,321,2) | 254.72 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb5kpc_iontable_hr.h5) |
| starburst-1kpc  | HDF5 | Low (27,81,2) | 16.58 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb1kpc_iontable_lr.h5) |
| starburst-1kpc  | HDF5 | High (105,321,2) | 254.72 MB | [Download](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases/latest/download/sb1kpc_iontable_hr.h5) |

## 3. Download

All datasets are available individually through the download links above or collectively from the [GitHub Releases](https://github.com/cPhysPlus/heating-cooling-ion-tables/releases) page.

The complete dataset comprises 12 files with a total download size of approximately **821.49 MB (0.82 GB)**.

## 4. Software

The datasets were generated using [py4radiation](https://github.com/cPhysPlus/py4radiation), together with the Cloudy code and Starburst99.

## 5. Citation

If you download and use these datasets in your research, please cite the following reference:

Reference paper to be added.

## 6. Licence

Copyright (c) 2026 Universidad Yachay Tech.

The datasets are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE) licence.

## 7. Authors

Authored by D. Villarruel-Yánez, W. E. Banda-Barragán & B. Casavecchia.
