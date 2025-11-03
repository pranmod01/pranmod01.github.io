---
title: "Exploring Cortical and Muscular Responses to Voluntary and EMS-Evoked Motion"
excerpt: "Investigating EEG–EMG signatures of voluntary vs electrically stimulated supinator activation<br/>"
collection: portfolio
date: 2025-09-25
status: "In Progress"
tags:
  - EEG
  - EMG
  - EMS
  - Neuroscience
  - Signal Processing
---

## Overview

This project investigates how the brain’s motor cortex responds during **voluntary versus externally-evoked muscle motion**. Using a combined EEG + EMG + EMS setup, we study the **supinator muscle**, which rotates the forearm, to compare cortical and muscular activity across three conditions: voluntary movement, motor imagery, and EMS-triggered motion.  

The project is being conducted for **COMS:4995 — Computation and the Brain (Fall 2025)** at Columbia University.

## Motivation

While EEG–EMG studies and electrical stimulation experiments exist independently, few directly compare cortical signatures of voluntary versus externally-evoked activation in the same muscle. Understanding these differences can inform neuroscience, brain-computer interfaces, and applied rehabilitation systems.

## Technical Details

### Technologies Used
- **OpenBCI Ganglion Board** — 4-channel EEG recording (C3/C4/Cz/CP3)  
- **Surface EMG electrodes** — supinator muscle  
- **Backyard Brains Human-to-Human Interface** — two-channel EMS stimulation  
- **Python / MNE** — data processing, event-related potentials, time–frequency analysis  

### Methodology
- Record EEG and EMG signals under voluntary movement, motor imagery, and EMS-induced motion  
- Synchronize stimulation with recordings for time-locked analysis  
- Extract **mu (8–13 Hz)** and **beta (13–30 Hz)** band features, readiness potentials, and post-stimulation cortical rebound  
- Compare anticipatory vs feedback-driven cortical activity patterns  

## Current Progress

- Hardware and signal quality verified separately for EEG, EMG, and EMS  
- Electrode placement and timing synchronization in progress  
- Pilot data collection planned for next steps  

## What I’m Learning

- Practical EEG and EMG data acquisition and preprocessing  
- Event-related potential analysis and time–frequency decomposition  
- Synchronization of external stimulation with neurophysiological recordings  

## Future Work

- Collect and analyze pilot trials  
- Quantify cortical differences between voluntary, imagined, and EMS-driven motion  
- Explore implications for corticomuscular coherence and motor control research  

---

**Project Status:** In Progress  
**Timeline:** September 2025 – December 2025  
