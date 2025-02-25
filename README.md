# Nonverbal Dynamics in Dyadic Videoconferencing Interaction

This repository contains R scripts and data for the paper:

> **C. Diao, S. A. Arboleda, and A. Raake.** Effects of Delay on Nonverbal Behavior and Interpersonal Coordination in Video Conferencing. In 2024 IEEE 26th International Workshop on Multimedia Signal Processing (MMSP), West Lafayette, IN, USA, 2024, pp. 1-6, doi:10.1109/MMSP61759.2024.10743300.  


The R scripts are for analyzing behavioral coordination data using Cross-Recurrence Quantification Analysis (CRQA), Growth Curve Analysis (GCA), and Linear Mixed Models (LMMs).
The analysis is focused on body motion and gaze behavior under different delay conditions.
## 📖 Abstract
This paper examines the impact of transmission delay (with 3 levels of transmission delay) on nonverbal behavior and interpersonal coordination during videoconferencing. Webcam recordings were analyzed to extract nonverbal cues and assess how delay disrupts body movement synchrony and facial expression mimicry.

## 📂 Repository Structure
- `data/`: Raw and processed experimental data.
- `scripts/`: R scripts for statistical analysis.
- `results/`: Outputs and plots.
- `README.md`: Project documentation.

## 📝 Analysis Breakdown
**CRQA & DCRP Analysis**  
(crqa_drcp_measure.Rmd)  
- Compute embedding delay, radius, and recurrence.
- Perform Cross-Recurrence Quantification Analysis (CRQA) to study body movement coordination.
- Compute Diagonal Cross-Recurrence Profile (DCRP) to assess how interpersonal coordination evolves over time.

**Statistical Modeling**  
(statistic_analysis.Rmd)
- Z-score normalization for body motion and gaze data.
- Linear Mixed Models (LMMs) to analyze gaze and motion behaviors.
- Growth Curve Analysis (GCA) to track changes in coordination over time

## 🛠 Setup
To set up the R environment, install dependencies:
```r
install.packages(c("ggplot2", "dplyr", "lme4", "crqa", "rstatix", "sjPlot", "performance"))
```

**Citation**
If you use this work, please cite:
```@inproceedings{10.1145/3678957.3685733,
author = {Diao, Chenyao and Arevalo Arboleda, Stephanie and Raake, Alexander},
title = {Nonverbal Dynamics in Dyadic Videoconferencing Interaction: The Role of Video Resolution and Conversational Quality},
year = {2024},
isbn = {9798400704628},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3678957.3685733},
doi = {10.1145/3678957.3685733},
booktitle = {Proceedings of the 26th International Conference on Multimodal Interaction},
pages = {387–396},
numpages = {10},
location = {San Jose, Costa Rica},
series = {ICMI '24}
}
```
