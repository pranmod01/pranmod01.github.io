---
title: "Perceptrons and Neural Representations"
excerpt: "Comparing spiking neural networks and CNNs in visual working memory tasks<br/>"
collection: portfolio
date: 2024-07-15
status: "Completed"
tags:
  - Spiking Neural Networks
  - Computational Neuroscience
  - Visual Working Memory
  - Neuromatch Academy
github: "https://github.com/pranmod01/perceptrons-neuromatch"
---

## Overview

This project, conducted as part of the **Neuromatch Academy NeuroAI program**, explores how **spiking neural networks (SNNs)** and **convolutional neural networks (CNNs)** represent visual information in working memory tasks. Using the MNIST dataset, we compared performance, robustness, and representational similarity across architectures.

## Motivation

Neuroscience-inspired AI models aim to bridge the gap between biological plausibility and computational efficiency. This project investigates whether biologically grounded spiking models can achieve comparable task performance to CNNs while offering insight into neural representation mechanisms. 

We want to examine the following questions:
1. How do spiking neural networks (SNNs) compare to traditional convolutional neural networks (CNNs) in encoding visual information for working memory tasks
2. How do different memory architectures (RNN and SNN) handle maintenance and retrieval of encoded visual information in delayed match-to-sample tasks?
3. How does the performance of an RNN and an SNN degrade as a function of increasing noise (delay) added during either the encoding or the maintenance phase of the task? Which architecture exhibits more robust representations?

## Technical Details

### Methodology
- Implemented CNN and SNN models trained on MNIST classification and short-term memory variants  
- Measured accuracy, robustness to noise and representational similarity across layers  
- Compared energy efficiency and response dynamics  

## Key Findings

- CNNs maintained higher accuracy, but SNNs showed greater robustness to temporal noise  
- Representational analysis suggested overlapping but temporally distinct encoding mechanisms  
- Highlights potential trade-offs between biological realism and computational performance  

## What I Learned

- Implementing and tuning spiking neural networks for cognitive tasks  
- Quantitative approaches to comparing biological and artificial neural representations  
- Interpreting emergent properties of neural architectures in working memory contexts  

## Links

- [GitHub Repository](https://github.com/pranmod01/perceptrons-neuromatch)

---

**Project Status:** Completed  
**Timeline:** July 2024  
