# Unified Spectral Geometry: Yang-Mills, Navier-Stokes & KPP Flow

## What this is

This repository contains the complete code and documentation for the unification of two Millennium Prize problems — Yang-Mills confinement and Navier-Stokes regularity — under a common Riemannian spectral geometry.

The work establishes that both phenomena arise from the same geometric object: a spectral metric defined on the space of frequencies or wavenumbers.

## Core idea

In Yang-Mills theory, the spectral density vanishes at a critical point, creating a geometric horizon that confines color charges. In Navier-Stokes turbulence, the spectral density remains positive, preventing any horizon and ensuring regularity.

Confinement and regularity are therefore dual geometric conditions on the same class of spectral manifolds.

## Key results

- The KPP flow equation is identified as the spectral Ricci flow of the spectral metric
- The universal coefficients (trace anomaly in Yang-Mills, Betchov invariant in Navier-Stokes) are the same geometric constraint in two physical realizations
- The critical dimension is exactly 4 in both systems
- A concrete cross-prediction: the energy spectrum in the Navier-Stokes inertial range should follow a sech² profile, departing from the classical Kolmogorov k^(-5/3) law
- An instanton-burst correspondence: the same action formula controls vacuum tunneling in Yang-Mills and intermittent bursts in turbulence

## Repository structure
├── paper.pdf # Full article with proofs and derivations
├── src/
│ └── unified_validation.py # Main validation script
├── data/
│ ├── ym_parameters.json # Yang-Mills spectral parameters
│ └── ns_parameters.json # Navier-Stokes spectral parameters
├── figures/ # Generated plots
├── requirements.txt # Python dependencies
├── LICENSE # MIT License
└── README.md


## How to reproduce

```bash
# Install dependencies
pip install -r requirements.txt

# Run the validation script
python src/unified_validation.py


## How to reproduce

```bash
# Install dependencies
pip install -r requirements.txt

# Run the validation script
python src/unified_validation.py

The script verifies:

Geodesic distances and curvature of the spectral manifold

Yang-Mills observables (string tension, glueball masses, deconfinement temperature)

Navier-Stokes regularity criterion and Betchov invariant

The universal coupling formula

The instanton-burst correspondence

All cross-predictions

Requirements
Python 3.8+

NumPy

SciPy

Matplotlib (optional, for figures)

Companion papers
This work builds on two previous articles:

From Yang-Mills to the KPP Flow: An Effective Theory of IR Confinement (Guiffra, 2026a)

Four-Variable Reduced System for Navier-Stokes Turbulence (Guiffra, 2026b)

Status
The geometric unification is established theoretically and numerically validated for both systems. The framework provides testable predictions for future experiments and simulations.

Citation
If you use this work, please cite:

P. Guiffra. Riemannian Spectral Geometry: Yang-Mills, Navier-Stokes and the KPP Flow. OSF, June 2026.

License
MIT License — free to use, modify, and distribute.

Contact
For questions or comments, please open an issue on this repository.
