[cite_start]**Course:** Neural Signal Processing [cite: 5]
[cite_start]**Authors:** Muralidhar Rao M, Prateek Kumar, Shreeansh Hota [cite: 4]

---

## Project Overview
[cite_start]This project investigates the "Shape of Stillness" hypothesis: the transition from a resting state to focused meditation is not merely signal amplification, but a collapse of degrees of freedom[cite: 38, 39]. [cite_start]Rather than treating the brain as a static array of independent channels or a "Black Box" pattern generator [cite: 36, 62][cite_start], this research aims to show that focus leads to the emergence of a low-dimensional neural manifold with high temporal stability[cite: 40]. 

## Dataset
* [cite_start]**Source:** Biswas et al. [cite: 119]
* [cite_start]**Data Type:** High-density 64-channel EEG[cite: 120].
* [cite_start]**Subjects:** 30 Rajyoga practitioners and 30 Controls[cite: 121].
* [cite_start]**Conditions:** EO1 (Baseline) versus M1 (Meditation)[cite: 122].

## Methodology
[cite_start]The analysis framework is divided into three main tiers[cite: 92]:

### 1. Signal Subspace Extraction
* [cite_start]Utilizes Principal Component Analysis (PCA) combined with Horn's Parallel Analysis[cite: 124].
* [cite_start]**Purpose:** Collapses correlated electrodes to handle volume conduction and filters out high-frequency noise that does not contribute to the cognitive state[cite: 125, 126].

### 2. Quantitative Metrics Analysis
[cite_start]Calculates three dynamical markers within the k-dimensional signal subspace[cite: 132]:
* [cite_start]**Trajectory Velocity:** Measures the Euclidean distance between consecutive time points to proxy volatility[cite: 133].
* [cite_start]**State Space Volume:** Measures the volume of the hyper-ellipsoid enclosing the trajectory to quantify dynamic range[cite: 133].
* [cite_start]**Excursion Radius:** Measures the mean distance of trajectory points from the geometric centroid to assess spatial spread[cite: 133].

### 3. Intrinsic Complexity & Visualization
* [cite_start]**Two-Nearest Neighbors (TNN) Estimator:** Used to estimate the true non-linear degrees of freedom ($d$), as linear methods like PCA can overestimate dimensionality in curved manifolds[cite: 139, 140, 141].
* [cite_start]**Mapping Attractor Topology:** Projects trajectories onto PC1–PC3 for visual inspection of stable loops versus chaotic wandering[cite: 100, 101, 102].

## Expected Outcomes
* [cite_start]**Metric Reduction:** Meditators are expected to show reduced Trajectory Velocity and State Space Volume, confirming the "Shape of Stillness" hypothesis[cite: 162, 163].
* [cite_start]**Lower Intrinsic Complexity:** A significant decrease in the Intrinsic Dimension ($d$) via TNN compared to the control group[cite: 164, 165].
* [cite_start]**High Reliability:** A lower standard deviation of $d$ within the meditation group, indicating that long-term practice drives neural dynamics toward a shared, stable complexity regime[cite: 166, 167, 168].