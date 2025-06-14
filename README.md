---
type: "project"
date: "2025-06-15"
title: "Using RSFC to Predict Early Language & Phonological Processing Abilities"
github_repo: https://github.com/chiapie/janet-chen_project
tags: [fmri, rsfc, language]
summary: "This project examined the relationship between resting-state functional connectivity (RSFC) and early speed naming and phonological processing in preschoolers. Using the Destrieux (2009) atlas, ROI-wise signals were extracted to compute within-network connectivity (e.g., DMN, language network), revealing correlations with behavioral scores."
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Resting-state functional connectivity (RSFC) reflects the brain’s intrinsic network organization in the absence of task demands. Prior research has shown that children with developmental dyslexia (DD) exhibit reduced connectivity between left temporal-frontal regions–key areas for language processing–and increased connectivity within the default mode network (DMN) compared to typically developing (TD) readers (Schurz et al., 2015). 

This project aims to investigate the relationship between RSFC and early phonological and language abilities in preschool children.


### Tools

This project used:
 * Python (Google Colab) & Excel
 * `nilearn` for ROI-wise extraction and brain visualization 
 * `pandas` & `numpy` for data analysis
 * `matplotlib` & `seaborn` for data visualization

### Data

Reynolds, J., Long, X., Paniukov, D., Bagshawe, M., Dewey, D., & Lebel, C. (2023, June 13). Calgary Preschool MRI Dataset. https://doi.org/10.17605/OSF.IO/AXZ5R

### Deliverables

- Project slide: https://docs.google.com/presentation/d/1Qv_kKj4uIC7enOUea1mDupAcgzFz-JtHmtoqQdst6L8/edit?usp=sharing
- Scatter plot 'age vs. speed naming number corrected'
- Whole-brain RSFC connectome
- Correlation between network strength and behavioral scores

## Results

### Tools I learned during this project

- `nilearn` atlas-based ROI extraction & brain connectome plotting
- `pandas` & `numpy` data cleaning & analysis; correlation matrix with fMRI signals to behavioral data
- `matplotlib` & `seaborn` for data visualization

### Results

#### Deliverable 1: Age vs. speed naming number of corrected items
The dataset only indicated that different speed-naming tasks were used for participants of different ages, but it did not specify which tasks were used. Only by plotting the items corrected for each age bracket did I infer that the same task was used for the 3–5, 5–7, and 7+ age groups.
<p align="center">
  <img src="scatterplot_age_speed.png" alt="Scatterplot of age vs. speed naming" width="640"/>
</p>

#### Deliverable 2: Whole-brain RSFC connectome
threshold = 0.99
<p align="center">
  <img src="whole-brain_RSFC_connectome.png" alt="Whole-brain RSFC connectome" width="600"/>
</p>

#### Deliverable 3: Correlation between network strength and behavioral scores results plots
*Examined network*
- Default Mode Network (DMN)
- Language Network
- Visual Attention & Scanning
<p align="center">
  <img src="result_summary.png" alt="Results summary" width="660"/>
</p>

## Discussion
- The lack of significant results may be due to the small sample size (n = 15) and limited variability in behavioral measures (i.e., small standard deviations).
- The effects of repeated measurements should be considered in future analyses.
- It is worth noting that 'passive viewing' ≠ 'resting state'; the original dataset did not record which movie participants were passively viewing during scanning.
