# Subject-specific Modeling by Domain Adaptation for the Estimation of Subglottal Pressure from Neck-Surface Acceleration Signals

This repository contains the official implementation of the methods proposed in the paper:

> **Subject-specific modeling by domain adaptation for the estimation of subglottal pressure from neck-surface acceleration signals**  
> *Emiro J. Ibarra, Julián D. Arias-Londoño, Juan I. Godino-Llorente, Daryush D. Mehta, Matías Zañartu*  
> _Biomedical Signal Processing and Control, Volume 106, 2025, 107681_  
> [DOI: 10.1016/j.bspc.2025.107681](https://doi.org/10.1016/j.bspc.2025.107681)


## Overview

Subglottal pressure \(P_s\) is a physiologically critical variable for understanding voice production and diagnosing voice disorders. Direct measurement of $P_s$ is invasive and impractical for ambulatory monitoring. This work presents a method for estimating $P_s$ from non-invasive neck-surface acceleration (ACC) signals using a subject-specific machine learning framework that includes domain adaptation from synthetic to in vivo data.

The approach combines:
- Physiologically inspired synthetic data from a voice production model
- Neural network-based regression
- Transfer learning for domain adaptation to real-world subjects

## 📁 Contents

- MPL-TL-Control.ipynb`: Code for subglottal pressure estimation in LD2, Table 6, Control group (Section 3.1.2)
- Additional notebooks may be added for other sections


If you use this code or find it helpful in your own work, please cite the following article:

@article{IBARRA2025,
  title = {Subject-specific modeling by domain adaptation for the estimation of subglottal pressure from neck-surface acceleration signals},
  journal = {Biomedical Signal Processing and Control},
  volume = {106},
  pages = {107681},
  year = {2025},
  doi = {https://doi.org/10.1016/j.bspc.2025.107681},
  author = {Emiro J. Ibarra and Julián D. Arias-Londoño and Juan I. Godino-Llorente and Daryush D. Mehta and Matías Zañartu}
}

## 📁 Data Availability

The data used in this study were collected under institutional review board (IRB) protocols and are subject to strict privacy regulations. Due to these restrictions, the dataset cannot be publicly shared.


