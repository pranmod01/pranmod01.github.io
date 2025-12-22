---
title: "ArXivCode: Bridging Theory and Implementation in AI Research"
excerpt: "Semantic code search engine connecting arXiv papers to implementations using CodeBERT embeddings<br/>"
collection: portfolio
date: 2025-10-15
status: "Completed"
tags:
  - Information Retrieval
  - CodeBERT
  - Research Tools
  - Semantic Search
github: "https://github.com/ArXivCode/ArXivCode"
demo: "https://arxivcode-frontend-215017069058.us-central1.run.app/"
---

## Overview

A semantic code search engine that bridges the gap between academic research and practical implementation. Users can search theoretical concepts from arXiv papers and instantly retrieve corresponding code implementations with contextual explanations, accelerating the journey from paper to practice.

Developed for COMS:6998 — LLM-Based Generative AI Systems (Fall 2025) at Columbia University.

## Technical Approach

- **CodeBERT Embeddings:** 768-dimensional semantic vectors for deep code understanding
- **Hybrid Retrieval:** Optimized 60/40 weighting of semantic similarity and keyword matching
- **Dataset:** Curated corpus of 2,490 code snippets extracted from 196 ML/AI research papers
- **Pipeline:** Custom PDF parsing → code extraction → embedding generation → retrieval ranking
- **Stack:** Python, Streamlit, CodeBERT (microsoft/codebert-base), Google Cloud Run

## Key Features

- **Semantic Understanding:** Finds implementations even when query terms don't match code literally
- **Context-Aware Results:** Returns code snippets with paper metadata and explanations
- **Cross-Paper Discovery:** Identifies similar implementations across different research works
- **Scalable Architecture:** Cloud-deployed for reliable access and future dataset expansion

## Results & Impact

- Successfully deployed production system serving the research community
- Achieved effective retrieval across diverse ML domains (transformers, CNNs, RL, optimization)
- Hybrid approach outperformed pure semantic or keyword-only baselines
- Demonstrates practical application of transformer-based code understanding at scale

## What I Learned

- Implementing semantic search using pre-trained language models specialized for code
- Balancing semantic embeddings with traditional keyword matching for robust retrieval
- Architecting end-to-end ML systems from data ingestion through production deployment
- Extracting and processing code from academic PDFs while preserving context
- Optimizing retrieval systems for both relevance and interpretability

## Demo

Live at [arxivcode-frontend-215017069058.us-central1.run.app](https://arxivcode-frontend-215017069058.us-central1.run.app/)

---

**Status:** Completed | **Timeline:** Sep–Dec 2025
