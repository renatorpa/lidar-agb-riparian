# 🛰️ LiDAR–Allometry Equivalence and Biomass Modeling in Riparian Forests

This repository contains the data and R scripts used in the study:

> **"Evaluating the Equivalence Between UAV-based and LiDAR-derived Aboveground Biomass Estimates in Mediterranean Riparian Forests"**  
> and its follow-up:  
> **"Structural Predictors of Aboveground Biomass: LiDAR-derived Metrics Across Species"**

---

## 📦 Contents

📁 data/
├── AGB_2018.csv              # Biomass estimates from UAV/alometric models (2018)
├── metricas_LiDAR_2024.csv  # LiDAR-derived structural metrics per riparian object (2024)

📁 scripts/
├── modelagem_agb_lidar_inicial.R    # Initial script for regression and variable importance

📁 figures/
├── power_curve_TOST.png     # Empirical TOST power curves
├── bland_altman.png         # Agreement plots between methods

---

## 📊 Objectives

This repository supports two main analyses:

**Statistical equivalence analysis** between LiDAR-based and allometric AGB estimates using:
   - Bland–Altman plots with BCa bootstrap limits,
   - TOST with bootstrap-based power curves.
   
## Citation and Attribution

If you use or adapt this code or data, please cite the article(s):
	•	[Main article citation once published]
	•	[DOI or Zenodo link if repository is archived]

## 📫 Contact

For questions or collaborations, please contact:
Renato de Paula
rrpaula@fc.ul.pt

