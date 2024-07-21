---
layout: page
title: Blogs
order: 3
permalink: /blogs/
---

## Tutorials and Guides

Welcome to the Tutorials and Guides section! Below, you'll find detailed steps and explanations for various processes related to EEG data analysis and artifact removal.

### Tutorial 1: ASR Parameter Evaluation

In this tutorial, we demonstrate how to evaluate different ASR (Artifact Subspace Reconstruction) parameters and interpret the results. The script evaluates the performance of various ASR parameters and visualizes the results.

- **[Read the Tutorial](https://github.com/vpKumaravel/vpkumaravel.github.io/wiki/How-to-tune-ASR-parameter%3F)**

### Tutorial 2: LOF Threshold Evaluation

This tutorial covers the steps for evaluating LOF (Local Outlier Factor) threshold, which is a default bad channel detection method in the NEAR (Newborn EEG Artifact Removal) pipeline. The guide includes detailed code and explanations for each step of the process.

- **[Read the Tutorial](https://github.com/vpKumaravel/vpkumaravel.github.io/wiki/How-to-tune-LOF-threshold-parameter%3F)**

### Tutorial 3: NEAR step-by-step tutorial

In this tutorial, I show how to preprocess a given newborn EEG dataset using NEAR pipeline. I also have provided the methods to perform post-processing (FFT analysis) such that one could compare the results between unprocessed and NEAR-preprocessed EEG files.

- **[Read the Tutorial](https://github.com/vpKumaravel/vpkumaravel.github.io/wiki/Step%E2%80%90by-step-Tutorial-on-Newborns-EEG-Artifact-Removal-(NEAR)-pipeline)**

## References

Here are some key papers related to the methods and techniques discussed in our tutorials:

### 1. NEAR: An Artifact Removal Pipeline for Human Newborn EEG Data

- **Authors**: V.P. Kumaravel, E. Farella, E. Parise, and M. Buiatti
- **Journal**: Developmental Cognitive Neuroscience (Special Issue: EEG Methods for Developmental Cognitive Neuroscientists: A Tutorial Approach)
- **Year**: 2022
- **DOI**: [10.1016/j.dcn.2022.101068](https://doi.org/10.1016/j.dcn.2022.101068)

**Abstract**: This paper introduces NEAR, an artifact removal pipeline designed specifically for human newborn EEG data. The method addresses common artifacts and provides a robust solution for preprocessing EEG data.

### 2. Adaptable and Robust EEG Bad Channel Detection Using Local Outlier Factor (LOF)

- **Authors**: Velu Prabhakar Kumaravel, Marco Buiatti, Eugenio Parise, and Elisabetta Farella
- **Journal**: Sensors
- **Volume**: 22
- **Number**: 19
- **Article Number**: 7314
- **Year**: 2022
- **URL**: [Link to Article](https://www.mdpi.com/1424-8220/22/19/7314)
- **DOI**: [10.3390/s22197314](https://doi.org/10.3390/s22197314)

**Abstract**: This article presents a method for EEG bad channel detection using Local Outlier Factor (LOF). It highlights the adaptability and robustness of LOF in identifying problematic channels in EEG recordings.

Feel free to explore these tutorials and apply the methods to your own EEG data analysis tasks. If you have any questions or need further assistance, don't hesitate to reach out!