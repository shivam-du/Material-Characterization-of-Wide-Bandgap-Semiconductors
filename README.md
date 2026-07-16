# Material-Characterization-of-Wide-Bandgap-Semiconductors
Characterization of AlGaN/GaN wide bandgap semiconductor heterostructures on SiC substrates using XRD, XPS, Photoluminescence, and temperature-dependent Raman spectroscopy to study structural, optical, and chemical properties for HEMT applications.

# MATERIAL CHARACTERIZATION OF WIDE BAND GAP SEMICONDUCTORS

<p align="center">
  <img src="sample_structure/AlGaN_GaN_HEMT_Structure.png" width="700">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Semiconductor%20Materials-blue">
  <img src="https://img.shields.io/badge/Application-HEMT-green">
  <img src="https://img.shields.io/badge/Material-AlGaN%2FGaN-orange">
  <img src="https://img.shields.io/badge/Characterization-XRD%20%7C%20XPS%20%7C%20PL%20%7C%20Raman-red">
  <img src="https://img.shields.io/badge/Temperature%20Range--150%C2%B0C%20to%20200%C2%B0C-purple">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

---

## Project Overview

This project focuses on the characterization of wide band gap semiconductor materials used for next-generation high-power and high-frequency electronic devices.

The work investigates an **AlGaN/GaN heterostructure grown on a SiC substrate**, which is widely used in **High Electron Mobility Transistors (HEMTs)** for RF communication, radar systems, satellite communication, electric vehicles, and power electronics.

Multiple material characterization techniques were used to study the structural, optical, and chemical properties of the device structure and to understand the effect of temperature on material behavior.

---

# Device Structure

The investigated sample consists of:

- SiNx passivation layer
- AlN barrier layer
- GaN channel layer
- Carbon doped GaN buffer layer
- AlN nucleation layer
- SiC substrate

The polarization mismatch at the AlGaN/GaN interface leads to the formation of a high mobility **Two Dimensional Electron Gas (2DEG)** channel which enables high-speed operation in HEMTs.

<p align="center">
  <img src="sample_structure/AlGaN_GaN_HEMT_Structure.png" width="700">
</p>

---

# Objectives

- Study the structural quality of the heterostructure.
- Determine crystal orientation and lattice properties.
- Analyze optical emission characteristics.
- Investigate elemental composition and bonding states.
- Study temperature dependent phonon behavior.
- Evaluate material suitability for HEMT applications.

---

# Characterization Techniques

| Technique | Purpose |
|----------|---------|
| X-Ray Diffraction (XRD) | Crystal structure and orientation analysis |
| X-Ray Photoelectron Spectroscopy (XPS) | Surface composition and elemental analysis |
| Photoluminescence Spectroscopy (PL) | Optical characterization and bandgap estimation |
| Raman Spectroscopy | Phonon behavior and temperature analysis |
| UV-Visible Spectroscopy | Optical absorption studies |

---

# X-Ray Diffraction (XRD)

XRD analysis was performed to investigate crystal quality and identify dominant crystallographic planes.

## Major Observations

- Strong GaN (002) diffraction peak observed near **34.69°**
- SiC (006) substrate peak observed near **35.68°**
- Narrow Gaussian peak fitting indicates high crystal quality and good epitaxial growth.

## Results

### Full XRD Scan

<p align="center">
<img src="results/XRD/Full_XRD_Scan.png" width="700">
</p>

### GaN (002) Gaussian Fit

<p align="center">
<img src="results/XRD/GaN_002_Gaussian_Fit.png" width="500">
</p>

### SiC (006) Gaussian Fit

<p align="center">
<img src="results/XRD/SiC_006_Gaussian_Fit.png" width="500">
</p>

---

# X-Ray Photoelectron Spectroscopy (XPS)

XPS was used to determine elemental composition and chemical bonding information.

## Detected Elements

- Gallium (Ga)
- Nitrogen (N)
- Silicon (Si)
- Oxygen (O)
- Carbon (C)

## Results

### XPS Survey Spectrum

<p align="center">
<img src="results/XPS/XPS_Survey.png" width="700">
</p>

### Peak Table

| Element | Peak Binding Energy (eV) |
|----------|--------------------------|
| Si 2p | 100.93 |
| C 1s | 283.69 |
| N 1s | 397.19 |
| O 1s | 531.85 |
| Ga 2p | 1117.99 |

<p align="center">
<img src="results/XPS/Peak_Table.png" width="600">
</p>

---

# Photoluminescence Spectroscopy (PL)

PL analysis was carried out to study optical transitions and determine material quality.

## Major Observations

### GaN Near Band Edge Emission
- Peak wavelength: **364.67 nm**
- Corresponding bandgap: **3.40 eV**

### Defect Related Emission
- Peak wavelength: **494.75 nm**
- Indicates deep level defect states.

### SiC Substrate Emission
- Peak wavelength: **651.13 nm**

## Results

### Full PL Spectrum

<p align="center">
<img src="results/PL/Full_PL_Spectrum.png" width="700">
</p>

### GaN Peak Gaussian Fit

<p align="center">
<img src="results/PL/GaN_Peak_Fit.png" width="500">
</p>

### Defect Peak Analysis

<p align="center">
<img src="results/PL/Defect_Peak_Fit.png" width="500">
</p>

### SiC Peak Analysis

<p align="center">
<img src="results/PL/SiC_Peak_Fit.png" width="500">
</p>

---

# Raman Spectroscopy

Temperature dependent Raman measurements were performed from:

# -150°C to +200°C

to investigate phonon behavior and thermal stability of the heterostructure.

---

## Raman Modes

| Raman Mode | Approximate Position |
|------------|----------------------|
| E2 (High) | ~775 cm⁻¹ |
| A1 (LO) | ~965 cm⁻¹ |

---

## Major Observations

### Peak Position Shift
Raman peaks shift towards lower wavenumbers with increasing temperature due to lattice expansion and phonon softening.

### FWHM Broadening
The FWHM increases with temperature because of stronger phonon-phonon interactions.

### Intensity Variation
Peak intensity changes with temperature because of variations in carrier concentration and scattering mechanisms.

---

## Raman Results

### Complete Temperature Scan

<p align="center">
<img src="results/Raman/01_All_Temperature_Raman_Spectra.png" width="700">
</p>

### Stacked Raman Spectra

<p align="center">
<img src="results/Raman/02_Stacked_Raman_Spectra.png" width="700">
</p>

### High vs Low Temperature Comparison

<p align="center">
<img src="results/Raman/03_High_vs_Low_Temperature_Comparison.png" width="700">
</p>

### E2 Peak Shift

<p align="center">
<img src="results/Raman/04_E2_Peak_Shift_vs_Temperature.png" width="600">
</p>

### E2 FWHM

<p align="center">
<img src="results/Raman/05_E2_FWHM_vs_Temperature.png" width="600">
</p>

### E2 Intensity

<p align="center">
<img src="results/Raman/06_E2_Intensity_vs_Temperature.png" width="600">
</p>

### A1(LO) Peak Shift

<p align="center">
<img src="results/Raman/07_LO_Peak_Shift_vs_Temperature.png" width="600">
</p>

### A1(LO) FWHM

<p align="center">
<img src="results/Raman/08_LO_FWHM_vs_Temperature.png" width="600">
</p>

### A1(LO) Intensity

<p align="center">
<img src="results/Raman/09_LO_Intensity_vs_Temperature.png" width="600">
</p>

---

# Key Findings

- High crystal quality confirmed using XRD.
- Successful identification of constituent elements using XPS.
- Optical measurements confirm GaN band edge emission around 3.4 eV.
- Temperature dependent Raman measurements show phonon softening and linewidth broadening.
- Results indicate excellent suitability for high-power and high-frequency HEMT applications.

---

# Applications

- RF Power Amplifiers
- Satellite Communication
- 5G Base Stations
- Radar Systems
- Power Electronics
- Electric Vehicles
- Aerospace Electronics

---

# Repository Structure

```text
MATERIAL_CHARACTERIZATION_OF_WIDE_BAND_GAP_SEMICONDUCTORS
│
├── README.md
├── report/
├── sample_structure/
├── results/
│   ├── PL/
│   ├── XRD/
│   ├── XPS/
│   └── Raman/
│
├── raw_data/
│   ├── PL/
│   ├── XRD/
│   ├── XPS/
│   └── Raman/
│
└── analysis_scripts/
```

---

# Future Work

- Hall Effect Measurements
- AFM Surface Analysis
- TEM Imaging
- Device Fabrication and Electrical Characterization
- TCAD Simulation of AlGaN/GaN HEMTs

---

# Authors

Shivam Chaurasiya and Team

Department of Electronics and Communication Engineering  
Faculty of Technology  
University of Delhi

---

# Supervisor

Dr. Khushwant Sehra  
Faculty of Technology  
University of Delhi

Dr. Amol Singh  
Faculty of Technology  
University of Delhi


---

# License

This project is released under the MIT License.
