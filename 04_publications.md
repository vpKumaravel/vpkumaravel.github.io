---
layout: page
title: "Publications"
order: 4
permalink: /publications/
---

Here, I feature a selection of my publications. Below, you will find abstracts or descriptions of my recent work, along with links to the full publications.

## 1) NEAR: An artifact removal pipeline for human newborn EEG data<br>
**Abstract:** Electroencephalography (EEG) is arising as a valuable method to investigate neurocognitive functions shortly after birth. However, obtaining high-quality EEG data from human newborn recordings is challenging. Compared to adults and older infants, datasets are typically much shorter due to newborns’ limited attentional span and much noisier due to non-stereotyped artifacts mainly caused by uncontrollable movements. We propose Newborn EEG Artifact Removal (NEAR), a pipeline for EEG artifact removal designed explicitly for human newborns. NEAR is based on two key steps: 1) A novel bad channel detection tool based on the Local Outlier Factor (LOF), a robust outlier detection algorithm; 2) A parameter calibration procedure for adapting to newborn EEG data the algorithm Artifacts Subspace Reconstruction (ASR), developed for artifact removal in mobile adult EEG. Tests on simulated data showed that NEAR outperforms existing methods in removing representative newborn non-stereotypical artifacts. NEAR was validated on two developmental populations (newborns and 9-month-old infants) recorded with two different experimental designs (frequency-tagging and ERP). Results show that NEAR artifact removal successfully reproduces established EEG responses from noisy datasets, with a higher statistical significance than the one obtained by existing artifact removal methods. The EEGLAB-based NEAR pipeline is freely available at [link](https://github.com/vpKumaravel/NEAR)<br>
**Link:** [Read more](https://www.sciencedirect.com/science/article/pii/S1878929322000123)

## 2) Efficient artifact removal from low-density wearable EEG using artifacts subspace reconstruction<br>
**Abstract:** Light-weight, minimally-obtrusive mobile EEG systems with a small number of electrodes (i.e., low-density) allow for convenient monitoring of the brain activity in out-of-the-lab conditions. However, they pose a higher risk for signal contamination with non-stereotypical artifacts due to hardware limitations and the challenging environment where signals are collected. A promising solution is Artifacts Subspace Reconstruction (ASR), a component-based approach that can automatically remove non-stationary transient-like artifacts in EEG data. Since ASR has only been validated with high-density systems, it is unclear whether it is equally efficient on low-density portable EEG. This paper presents a complete analysis of ASR performance based on clean and contaminated datasets acquired with BioWolf, an Ultra-Low-Power system featuring only eight channels, during SSVEP sessions recorded from six adults. Empirical results show that even with such few channels, ASR efficiently corrects artifacts, enabling an overall enhancement of up to 40% in SSVEP response. Furthermore, by choosing the optimal ASR parameters on a single-subject basis, SSVEP response can be further increased to more than 45%. These results suggest that ASR is a viable and robust method for online automatic artifact correction with low-density BCI systems in real-life scenarios.<br>
**Link:** [Read more](https://ieeexplore.ieee.org/abstract/document/9629771)

## 3) Adaptable and Robust EEG Bad Channel Detection Using Local Outlier Factor (LOF)<br>
**Abstract:** Electroencephalogram (EEG) data are typically affected by artifacts. The detection and removal of bad channels (i.e., with poor signal-to-noise ratio) is a crucial initial step. EEG data acquired from different populations require different cleaning strategies due to the inherent differences in the data quality, the artifacts’ nature, and the employed experimental paradigm. To deal with such differences, we propose a robust EEG bad channel detection method based on the Local Outlier Factor (LOF) algorithm. Unlike most existing bad channel detection algorithms that look for the global distribution of channels, LOF identifies bad channels relative to the local cluster of channels, which makes it adaptable to any kind of EEG. To test the performance and versatility of the proposed algorithm, we validated it on EEG acquired from three populations (newborns, infants, and adults) and using two experimental paradigms (event-related and frequency-tagging). We found that LOF can be applied to all kinds of EEG data after calibrating its main hyperparameter: the LOF threshold. We benchmarked the performance of our approach with the existing state-of-the-art (SoA) bad channel detection methods. We found that LOF outperforms all of them by improving the F1 Score, our chosen performance metric, by about 40% for newborns and infants and 87.5% for adults.  <br>
**Link:** [Read more](https://www.mdpi.com/1424-8220/22/19/7314)

## 4) IMU-integrated Artifact Subspace Reconstruction for Wearable EEG Devices<br>
**Abstract:** Electroencephalography (EEG) provides unique insights into natural brain dynamics outside the laboratory setting. However, its usability is limited due to the presence of artifacts. Artifact Subspace Reconstruction (ASR) has been a popular method for enhancing the signal-to-noise ratio (SNR) in mobile EEG; nonetheless, its complexity restricts its applicability on lightweight, resource-constrained EEG devices. To address this challenge, we propose an innovative IMU-integrated approach for artifacts correction (IMU-ASR). Specifically, we replace ASR’s time-consuming calibration process with a simpler accelerometer-based method, significantly reducing computational time without compromising performance. We validate our approach on two publicly available datasets, one with low-density (8 channels) and the other with high-density (120 channels) EEG. Our findings demonstrate the potential of accelerometer-driven ASR for lightweight hardware-software EEG solutions, promising a more practical and efficient approach for artifact correction in mobile EEG applications. <br>
**Link:** [Read more](https://ieeexplore.ieee.org/abstract/document/10385390)

## 5) Efficient Low-Frequency SSVEP Detection with Wearable EEG Using Normalized Canonical Correlation Analysis<br>
**Abstract:** Recent studies show that the integrity of core perceptual and cognitive functions may be tested in a short time with Steady-State Visual Evoked Potentials (SSVEP) with low stimulation frequencies, between 1 and 10 Hz. Wearable EEG systems provide unique opportunities to test these brain functions on diverse populations in out-of-the-lab conditions. However, they also pose significant challenges as the number of EEG channels is typically limited, and the recording conditions might induce high noise levels, particularly for low frequencies. Here we tested the performance of Normalized Canonical Correlation Analysis (NCCA), a frequency-normalized version of CCA, to quantify SSVEP from wearable EEG data with stimulation frequencies ranging from 1 to 10 Hz. We validated NCCA on data collected with an 8-channel wearable wireless EEG system based on BioWolf, a compact, ultra-light, ultra-low-power recording platform. The results show that NCCA correctly and rapidly detects SSVEP at the stimulation frequency within a few cycles of stimulation, even at the lowest frequency (4 s recordings are sufficient for a stimulation frequency of 1 Hz), outperforming a state-of-the-art normalized power spectral measure. Importantly, no preliminary artifact correction or channel selection was required. Potential applications of these results to research and clinical studies are discussed.<br>
**Link:** [Read more](https://www.mdpi.com/1424-8220/22/24/9803)

## 6) Interpretable CNN for Single-Channel Artifacts Detection in Raw EEG Signals<br>
**Abstract:** Electroencephalogram (EEG) signals recorded from the scalp are often affected by artifacts. Most existing artifact detection methods rely on multi-channel statistics such as inter-channel correlation. Recently, there has been a growing interest in realizing single-channel EEG systems to promote everyday use, demanding novel artifacts detection techniques. This paper presents validation results for single-channel artifacts detection in raw EEG signals using four neural architectures: a one-dimensional CNN (1D-CNN) - proposed by us, EEGNet, SincNet and EEGDenoiseNet. We used semi-synthetic EEG data corrupted with Ocular (EOG) and Myo-graphic (EMG) noise components to validate the approaches. Precisely, we contaminated the randomly chosen EEG channels with EOG and EMG artifacts in a controlled manner using a predefined Signal-to-Noise Ratio (SNR) such that the ground truth is known. We validated these models both in terms of classification performance and the interpretability of the learned features. Of the four models, 1D-CNN, EEGNet, and SincNet achieved a comparable classification accuracy (around 99%) and EEGDenoiseNet achieved as low as 64%. Analysing the learned filters for interpretability, we found both 1D-CNN and EEGNet clearly separates EOG (Delta and Theta) and EMG (Gamma) frequency bands from EEG. Instead, SincNet prioritized to learn EEG-specific features (Alpha and Beta) rather than artifact-related information still achieiving the comparable performance as the other two models. EEGDenoiseNet with kernel width of 3 was excluded from this evaluation as it is practically infeasible to perform FFT analysis. Finally, we also computed the number of training parameters for each model to evaluate which among them would be suitable for a resource-constrained wearable device and we found that 1D-CNN and SincNet are the most parameter-efficient, although not by a large margin.<br>
**Link:** [Read more](https://ieeexplore.ieee.org/abstract/document/9881381)