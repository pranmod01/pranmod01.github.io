---
title: "AI Slop Detector: Multi-Agent Quality Assessment System"
excerpt: "Fine-tuned small language models detecting low-quality AI outputs using specialized evaluators<br/>"
collection: portfolio
date: 2025-11-20
status: "Completed"
tags:
  - Small Language Models
  - LoRA
  - AWS Trainium
  - Quality Detection
github: "https://github.com/pranmod01/ai-slop-detector"
---

## Overview

A multi-agent system that identifies "AI slop"—low-quality, incoherent model outputs that evade basic quality filters. Built for the AWS Small Language Build Day Hackathon, the system uses four specialized small language models (1-3B parameters) with LoRA adapters to serve as an early warning mechanism before expensive moderation stages.

## Technical Approach

- **Multi-Agent Architecture:** 4 fine-tuned SLMs targeting specific quality signals
  - Genericity Detector: Identifies vague, semantically shallow language
  - Substance Analyzer: Measures information density and topical grounding
  - Style Analyzer: Captures synthetic text patterns and lexical regularity
  - Repetition Detector: Flags templated artifacts and autoregressive repetition
- **Models:** Qwen 2.5 (1.5B) + 4 LoRA adapters (~5MB each)
- **Ensemble Voting:** Integrates judgments across evaluators
- **Compute:** AWS Trainium (trn1.2xlarge) with Neuron SDK
- **Stack:** PyTorch, Transformers, PEFT

## Key Advantages

- **Interpretability:** Specialized evaluators expose decision drivers
- **Efficiency:** Real-time evaluation capability, ~10× cheaper than large-model inference
- **Generalization:** Tests across model families (GPT vs Qwen)
- **Transparency:** Trustable monitoring pipeline

## What I Learned

- Designing multi-agent architectures where specialized models collaborate on complex classification tasks
- Fine-tuning small language models efficiently using LoRA adapters for targeted quality assessment
- Working with AWS Trainium accelerators and the Neuron SDK for cost-effective training
- Balancing model size, inference speed, and accuracy in production-oriented quality detection systems
- Implementing ensemble voting strategies to combine multiple evaluation signals into robust decisions

---

**Status:** Completed | **Timeline:** Nov 2025
