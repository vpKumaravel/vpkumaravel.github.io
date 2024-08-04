---
layout: page
title: "Projects"
order: 2
permalink: /projects/
---

**Speech Perception In Noise Enhancement (SPINE) via EEG-based Neurofeedback**

I am awarded a fully funded research grant for a period of 2 years (of which 9 months will be spent as a residential fellowship) to work on this project. The goal is to determine if neurofeedback on auditory selective attention enhances the perception of speech in noisy environments in everyday life. The hypothesis is that providing users with feedback on their auditory selective attention skills (assessed through the classical competing speech paradigm) enables them to adjust their perceptual abilities, thereby improving their performance in speech-in-noise tasks.  I collaborate with Prof. Dr. Stefan Debener and Dr. Martin Bleichner from the Department of Psychology (Neuropsychology Lab), University of Oldenburg, Germany.

**Newborn EEG Artifact Removal (NEAR) Pipeline**

One of the challenges in studying human cognitive development is the lack of reliable neural feature extraction from noisy neuroimaging data. My (primary) goal within my PhD research was to develop signal processing methodologies that can overcome such limitations. As a result, I developed a fully automated preprocessing pipeline to remove/filter out artifacts from EEG collected from newborns of 0-4 days old and infants of 9-months old. The pipeline is based on the EEGLAB software and is freely available [here](https://github.com/vpKumaravel/NEAR). 

**Automatic Noisy/Bad EEG Sensors Detection**

Detecting and removing noisy sensors (such as flat-line sensors) is one of the common preprocessing steps in EEG and MEG data analysis pipeline. I introduced a novel, density-based bad channel detection using the Local Outlier Factor (LOF) algorithm. The novelty is that the method does not assume any distribution for the data and employs nearest neighbors approach to find the sensors that 'locally' deviated from its neighbors. More information can be found [here](). The algorithm is available as EEGLAB plugin (download [here](https://github.com/vpKumaravel/detectbadchannelLOF/blob/main/README.md)),  MEEG-kit (download [here](https://github.com/nbara/python-meegkit/blob/master/meegkit/lof.py)) and MNE-Python (download [here](https://mne.tools/stable/generated/mne.preprocessing.find_bad_channels_lof.html#mne.preprocessing.find_bad_channels_lof)) .
