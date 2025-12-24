# Deep and Shallow Precipitation Regimes over India (2014–2024)

This repository presents a comprehensive characterization of **convective, stratiform, and shallow precipitation regimes over India** using **11 years (2014–2024) of GPM Dual-Frequency Precipitation Radar (DPR) Ku-band data**.  
The study focuses on the **spatial distribution, vertical structure, diurnal variability, and thermodynamic controls** of different rain types during the Indian Summer Monsoon.

---

## 📌 Scientific Motivation

India’s rainfall is shaped by complex interactions between monsoon dynamics, orography, and atmospheric thermodynamics.  
While satellite rainfall products estimate rain intensity, they often **do not distinguish precipitation types**, leading to large uncertainties in:

- Extreme rainfall estimation  
- Flood forecasting  
- Numerical weather prediction  
- Climate model evaluation  

This work establishes a **physically grounded precipitation-type baseline** over India using spaceborne radar observations.

---

## 🎯 Objectives

1. **Characterize precipitation regimes** (convective, stratiform, shallow) over India using GPM-DPR vertical profiles.
2. **Analyze vertical structure and microphysics** using reflectivity profiles and CFADs.
3. **Examine diurnal variability** of precipitation frequency and intensity.
4. **Quantify environmental controls** using ERA5 thermodynamic variables (CAPE, TCWV).
5. **Provide a physical foundation** for future AI / deep-learning–based precipitation classification using geostationary satellites (INSAT).

---

## 🛰️ Datasets Used

### Primary Data
- **GPM-DPR Ku-band (2Ku)**  
  - Vertical radar reflectivity profiles  
  - Near-Surface Rain Rate (NSR)  
  - Storm Top Height (STH)  
  - Precipitation type flags  

### Environmental Data
- **ERA5 Reanalysis**
  - Convective Available Potential Energy (CAPE)
  - Total Column Water Vapor (TCWV)

### Future Integration
- **INSAT-3DR** multispectral infrared observations (for AI-based classification)

> ⚠️ Large satellite data files are not included in this repository.  
> Data can be accessed from NASA GES DISC and Copernicus Climate Data Store.

---

## 🧪 Methodology Overview

1. **Data acquisition** of GPM-DPR and ERA5 datasets  
2. **Quality control and filtering** of radar profiles  
3. **Rain-type identification** using GPM-DPR classification flags  
4. **Feature extraction** (NSR, STH, reflectivity profiles)  
5. **Spatial and diurnal analysis** across India  
6. **Environmental analysis** linking rain types with CAPE and TCWV  
7. **Framework development** for ML-ready precipitation classification  

---

## 📊 Key Analyses Performed

- Spatial climatology of precipitation types  
- Vertical structure and mean reflectivity profiles  
- CFADs (Contoured Frequency by Altitude Diagrams)  
- Diurnal cycle of precipitation frequency and intensity  
- TCWV–NSR and CAPE–precipitation relationships  

---

## 🛠️ Tools & Technologies

- **Python**
  - numpy, pandas, xarray
  - matplotlib
- **Satellite & Radar Meteorology**
- **Climate Data Analysis**
- **Physical interpretation for AI readiness**
- **Git & GitHub for version control**

---

## 🚀 Applications & Impact

- Improved understanding of Indian monsoon rainfall physics  
- Physically interpretable precipitation datasets for AI/ML models  
- Enhanced satellite rainfall estimation strategies  
- Support for flood risk and climate studies  

---

## 👨‍🎓 Author

**Naveen Baipilli**  
M.Tech – Climate Change  
Indian Institute of Technology  
Research focus: Satellite meteorology, precipitation physics, AI for climate

---

## 📄 License

This project is intended for **academic and research use**.  
Please cite appropriately if used in publications.
