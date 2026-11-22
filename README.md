# Catalogue: py4radiation Datasets

This repository provides ready-to-use datasets generated with [py4radiation](https://github.com/cPhysPlus/py4radiation), including:

- **Heating and cooling functions in ASCII format:** these can be readily coupled to any existing hydrodynamic code, like [PLUTO/gPLUTO](https://plutocode.ph.unito.it).
  
- **Ion fraction tables in HDF5 format:** these can be readily coupled to post-processing tools, like [Trident](https://github.com/trident-project/trident).

## Data Description

### 1. Tabulated Heating and Cooling Functions

The datasets are organised into three groups, each containing two files at different resolutions.

| Radiation Field | Format | Resolution ($n_{\rm H},T$) | File size | Download |
|:----------------|:------:|:----------------------------:|:---------:|:--------:|
| meta-galactic   | ASCII | Low ($27, 81$) | 160 KB | [Low resolution](./heating_cooling/metagalactic_low.dat) |
| meta-galactic   | ASCII | High (105, 321) | 2.4 MB | [High resolution](./heating_cooling/metagalactic_high.dat) |
| starburst-5kpc  | ASCII | Low (27, 81) | 160 KB | [Low resolution](./heating_cooling/starburst_5kpc_low.dat) |
| starburst-5kpc  | ASCII | High (105, 321) | 2.4 MB | [High resolution](./heating_cooling/starburst_5kpc_high.dat) |
| starburst-1kpc  | ASCII | Low (27, 81) | 160 KB | [Low resolution](./heating_cooling/starburst_1kpc_low.dat) |
| starburst-1kpc  | ASCII | High (105, 321) | 2.4 MB | [High resolution](./heating_cooling/starburst_1kpc_high.dat) |

### 2. Tabulated Ion Fraction Tables

Ion fraction tables are provided in HDF5 format for the same three radiation fields and two resolutions.

| Radiation Field | Format | Resolution ($n_{\rm H},T,z$) | File size | Download |
|:----------------|:------:|:----------------------------:|:---------:|:--------:|
| meta-galactic   | HDF5 | Low (27,81,2) | 17 MB | [Low resolution](./ion_fractions/metagalactic_low.h5) |
| meta-galactic   | HDF5 | High (105,321,2) | 255 MB | [High resolution](./ion_fractions/metagalactic_high.h5) |
| starburst-5kpc  | HDF5 | Low (27,81,2) | 17 MB | [Low resolution](./ion_fractions/starburst_5kpc_low.h5) |
| starburst-5kpc  | HDF5 | High (105,321,2) | 255 MB | [High resolution](./ion_fractions/starburst_5kpc_high.h5) |
| starburst-1kpc  | HDF5 | Low (27,81,2) | 17 MB | [Low resolution](./ion_fractions/starburst_1kpc_low.h5) |
| starburst-1kpc  | HDF5 | High (105,321,2) | 255 MB | [High resolution](./ion_fractions/starburst_1kpc_high.h5) |

## 3. Download

All datasets are available individually through the download links above or collectively from the [GitHub Releases](../../releases) page.

## 4. Software

The datasets were generated using [py4radiation](https://github.com/cPhysPlus/py4radiation), together with the Cloudy code and Starburst99.

## 5. Citation

If you download and use these datasets in your research, please cite the following reference:

Reference paper to be added.

## 6. Licence

Copyright (c) 2026 Universidad Yachay Tech.

The datasets are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE) licence.

Authored by D. Villarruel-Yanez, W. E. Banda-Barragan & B. Casavecchia.
