# Korg Spectrum Synthesis of Fornax with MAVIS

## Introduction

This repository hosts a Jupyter Notebook designed to compute synthetic stellar spectra for the Fornax dwarf spheroidal galaxy using the Korg spectral synthesis code. Korg is capable of generating stellar spectra from 1D model atmospheres and linelists, assuming local thermodynamic equilibrium.

## Author

**Sven Buder**  
ANU (Australian National University)  
Email: sven.buder@anu.edu.au

## Citation

When utilizing Korg for your research, please ensure to cite the following works:

- Wheeler et al. (2023), [AJ, 165, 68W](https://ui.adsabs.harvard.edu/abs/2023AJ....165...68W/abstract)
- Wheeler et al. (2024), [AJ, 167, 83W](https://ui.adsabs.harvard.edu/abs/2024AJ....167...83W/abstract)

For more detailed information about Korg, please refer to the [official Korg documentation](https://ajwheeler.github.io/Korg.jl/stable/).

## Installation

To run the provided Jupyter Notebook, you will need the following installed on your system:

- **Julia** programming language
  - Julia packages: `Korg`, `JLD2`, `FiloIO`, `Serialization`
- **Python**
  - Python package: `juliacall`

For instructions on installing Julia and the necessary packages, please refer to the [Korg installation guide](https://ajwheeler.github.io/Korg.jl/stable/install/#install).

## Notebook Overview

The main Jupyter Notebook includes sections on:

1. **Korg Input**: Specifications of wavelengths, line-spread-function matrix, and linelist.
2. **Korg Synthesis Call**: How to invoke Korg to compute the spectra.
3. **Example Application**: Demonstrates the use of Korg for generating synthetic spectra for the Sun and a sample star from Fornax.

This interface specifically computes synthetic Korg spectra for Fornax at MAVIS (3700-9400Å) wavelength and resolution (R=20,000).
