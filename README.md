# Effects of Delay on Nonverbal Behavior and Interpersonal Coordination in Video Conferencing

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

**Citation**
If you use this work, please cite:
```@inproceedings{diao2024effects,
  title={Effects of Delay on Nonverbal Behavior and Interpersonal Coordination in Video Conferencing},
  author={Diao, Chenyao and Arboleda, Stephanie Ar{\'e}valo and Raake, Alexander},
  booktitle={2024 IEEE 26th International Workshop on Multimedia Signal Processing (MMSP)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}
```
