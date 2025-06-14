---
type: "project"
date: "2025-06-15"
title: "Using RSFC to Predict Early Language & Phonological Processing Abilities"
github_repo: https://github.com/chiapie/janet-chen_project
tags: [fmri, rsfc, language]
summary: "This project investigated how resting-state functional connectivity (RSFC) in fMRI data from preschool children relates to early speed naming and phonological processing abilities. Using the Destrieux (2009) atlas, extracting ROI-wise brain signals and computed within-network connectivity strength across multiple brain networks (e.g., DMN, language network). Correlation analyses then revealed trends between network resting-state and behavioral scores."
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Resting-state functional connectivity (RSFC) reflects the brain’s intrinsic network organization in the absence of task demands. Prior research shows that children with developmental dyslexia (DD) exhibit reduced connectivity between left temporo-frontal regions—key areas for language processing—and increased connectivity within the default mode network (DMN) compared to typically developing (TD) readers (Schurz et al., 2015). This project aims to explore how RSFC relates to early phonological and language abilities in preschool-aged children.


### Tools

This project used:
 * Python (Google Colab) & Excel
 * `nilearn` for ROI-wise extraction and brain visualization 
 * `pandas` & `numpy` for data analysis
 * `matplotlib` & `seaborn` for data visualization

### Data

Reynolds, J., Long, X., Paniukov, D., Bagshawe, M., Dewey, D., & Lebel, C. (2023, June 13). Calgary Preschool MRI Dataset. https://doi.org/10.17605/OSF.IO/AXZ5R

### Deliverables

- Whole-brain heatmap
- 

## Results

### Progress overview

The project was swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

- `nilearn` atlas-based ROI extraction & brain connectome plotting
- Correlation matrix with fMRI signals to behavorial data
- `pandas` & `numpy` data cleaning & analysis
- `seaborn` for data visualization

### Results

#### Deliverable 1: report template

You are currently reading the report template! I will let you judge whether it is useful or not. If you think there is something that could be improved, please do not hesitate to open an issue [here](https://github.com/PSY6983-2021/project_template/issues/) and let us know.

#### Deliverable 2: project gallery

You can check out the [2020 BrainHack School project gallery](https://psy6983.brainhackmtl.org/project/)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Discussion
- The lack of significant results may be due to the small sample size (n = 15) and limited variability in behavioral measures (i.e., small standard deviations).
- The effects of repeated measurements should be considered in future analyses.
- It is worth noted that 'passive viewing' ≠ 'resting state'; the original dataset did not record which movie participants were passively viewing during scanning.