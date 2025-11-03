---
title: "ArXivCode: Bridging Theory and Implementation in AI Research"
excerpt: "Aligning AI papers and code repositories using fine-tuned LLMs<br/>"
collection: portfolio
date: 2025-10-15
status: "In Progress"
tags:
  - LLMs
  - Information Retrieval
  - Research Tools
  - Generative AI
github: "https://github.com/pranmod01/arxivcode"  
---

## Overview

**ArXivCode** aims to bridge the gap between AI research papers and their practical implementations by building a dual-model system that retrieves relevant code snippets and explains their connection to theoretical concepts. The project seeks to make research more reproducible, accessible, and actionable.

This project is being developed as part of COMS:6998 — LLM-Based Generative AI Systems (Fall 2025) at Columbia University.

## Motivation

Theoretical AI research often remains disconnected from real-world implementation. While ArXiv hosts cutting-edge papers and GitHub holds vast repositories of code, connecting the two remains manual and inefficient. ArXivCode aims to close this gap by enabling intelligent retrieval and alignment between papers and their implementations.

## Technical Details

### Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- FAISS
- LangChain
- FastAPI
- HTML/CSS/JavaScript (for demo interface)

### Architecture/Approach
ArXivCode integrates two fine-tuned models:
- A code understanding model (based on CodeBERT or StarCoder) that learns embeddings for semantic code retrieval.  
- A paper comprehension model (based on LLaMA or Mistral) that interprets theoretical descriptions and maps them to relevant code.  

A dense retrieval system with cross-encoder re-ranking ensures accurate mapping between paper sections and code snippets.

## Key Features

- Paper-to-code retrieval with fine-grained alignment  
- Natural language queries for theoretical concepts  
- Explanatory annotations connecting papers and code  
- Early prototype of web-based demo system  

More coming soon!

---

**Project Status:** In Progress  
**Timeline:** September 2025 – December 2025  
