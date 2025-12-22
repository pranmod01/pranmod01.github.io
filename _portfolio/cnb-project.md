---
title: "Exploring Cortical and Muscular Responses to Voluntary and EMS-Evoked Motion"
excerpt: "Analyzing motor cortex activity differences between voluntary movement and electrical muscle stimulation<br/>"
collection: portfolio
date: 2025-09-25
status: "Completed"
tags:
  - EEG
  - Neuroscience
  - Signal Processing
  - Motor Cortex
github: "https://github.com/pranmod01/eeg-ems-compare"
---

## Overview

Research analyzing brain activity differences between voluntary muscle movement and electrically-stimulated motor activation. The study investigates whether the motor cortex responds distinctly when muscles move by choice versus external electrical stimulation using 4-channel EEG across 5 experimental conditions.

Conducted for COMS: 6995 — Computation and the Brain (Fall 2025) at Columbia University.

## Methodology

- **EEG Setup:** 4-channel recording (C3, C4, Cz, CP3) at 200 Hz targeting motor cortex regions
- **Conditions:** Voluntary left/right movement, motor imagery, EMS, and passive stimulation
- **Analysis:** Spectral power analysis of mu (8-13 Hz) and beta (13-30 Hz) oscillations using MNE
- **Stack:** Python, MNE, NumPy, Pandas, Matplotlib, SciPy, Seaborn, interactive web viewer  

## Key Results

Motor imagery generated strongest cortical activity (2.68e-10 mu power), while EMS produced minimal response (1.63e-12), suggesting planning-dependent neural signatures. Voluntary movement fell between these extremes, indicating graded motor cortex engagement.

## What I Learned

- Designing and conducting human-subjects neuroscience experiments with proper protocols
- EEG signal acquisition, preprocessing, and artifact removal techniques using MNE
- Spectral analysis of oscillatory brain activity in motor control paradigms
- Comparing voluntary and involuntary motor pathways through cortical activation patterns
- Building reproducible analysis pipelines with interactive visualization for neuroscience data

---

**Status:** Completed | **Timeline:** Sep–Dec 2025  
