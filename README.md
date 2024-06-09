# Cognitive-Control-Related-to-the-Flanker-Task

## Overview

This report documents the analysis of fMRI data related to cognitive control using the Flanker Task. The primary objective is to understand the neural mechanisms underlying cognitive control and conflict resolution through detailed preprocessing, modeling, and analysis of fMRI data.

## Contents

1. **Introduction**
   - Overview of fMRI and its importance in neuroscience.
   - Objectives of the Flanker Task in studying cognitive control.
   - Summary of the analytical approach and methodologies used.

2. **Brain Anatomy**
   - Basic information on brain anatomy relevant to interpreting fMRI results.
   - Description of the cerebrum, cerebellum, brainstem, thalamus, and pons.

3. **Preprocessing**
   - Detailed steps of fMRI data preprocessing including motion correction, slice timing correction, spatial normalization, brain extraction (using BET), and spatial smoothing.
   - Importance of each preprocessing step in ensuring data accuracy and reliability.

4. **First Level Analysis**
   - Setup and execution of first-level analysis using FSL’s FEAT.
   - Motion correction and registration techniques.
   - Discussion on the impact of different degrees of freedom (DOF) in data mapping.

5. **Modeling**
   - Explanation of the modeling process, including the equations used.
   - Setup and results of the incongruent and congruent conditions of the Flanker Task.
   - Interpretation of the contrast results.

6. **Scripting**
   - Automation of preprocessing and modeling steps for multiple subjects using scripts.
   - Detailed scripting process to streamline the analysis and reduce manual effort.

7. **Second Level Analysis**
   - Combining results from individual analyses to perform group-level analysis.
   - Steps and methods used to average parameter and contrast estimates across subjects.

8. **Third Level Analysis**
   - Transition from second-level to group-level investigations.
   - Statistical techniques and modeling approaches for analyzing neural activations across subjects.

## Purpose

The report aims to provide a comprehensive analysis of fMRI data to understand cognitive control mechanisms. By following a structured methodology and utilizing advanced preprocessing and modeling techniques, the report ensures accurate and reliable results that contribute to the understanding of brain function during the Flanker Task.

## Steps Taken

- Conducted thorough preprocessing of fMRI data to ensure data quality.
- Applied first-level analysis to individual subjects to identify neural activation patterns.
- Automated preprocessing and modeling tasks using scripting to handle large datasets efficiently.
- Performed second-level analysis to combine individual results and derive group-level insights.
- Completed third-level analysis to validate and generalize findings across the population.

## Conclusion

This report provides a detailed account of the methods and findings related to the analysis of fMRI data from the Flanker Task. It highlights the importance of each analytical step and presents the results in a structured manner, contributing to the broader understanding of cognitive control mechanisms.
