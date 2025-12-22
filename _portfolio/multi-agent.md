---
title: "Multi-Drive Curiosity-Based RL Agent"
excerpt: "Biologically inspired RL agents integrating curiosity, survival, and safety drives for aligned behavior<br/>"
collection: portfolio
date: 2025-08-10
status: "In Progress"
tags:
  - Reinforcement Learning
  - AI Alignment
  - Curiosity
  - OpenAI Gym
github: "https://github.com/pranmod01/multi-drive-agent"
---

## Overview

An independent research project exploring **biologically inspired reinforcement learning agents** with multiple competing motivational drives: curiosity, survival, and safety. The agent learns to navigate OpenAI Gym environments while balancing exploration with alignment to intended objectives, addressing reward hacking and unsafe behavior patterns common in standard RL.

## Motivation

Standard RL agents often exploit reward functions in unintended ways—cutting corners, reward hacking, or exhibiting unsafe behaviors during exploration. By integrating multiple motivational drives inspired by biological systems (intrinsic curiosity, survival pressure, safety constraints), this project investigates whether more robust and naturally aligned AI behavior can emerge, providing insights into safe exploration and intrinsic motivation mechanisms.

## Technical Approach

- **Multi-Objective Reward Architecture:** Weighted combination of curiosity (novelty-seeking), survival (goal achievement), and safety (constraint satisfaction) signals
- **Policy Gradient Methods:** Custom actor-critic implementation with intrinsic reward modulation
- **Environment Suite:** Testing across multiple OpenAI Gym environments to validate generalization
- **Stack:** Python, PyTorch, OpenAI Gym, NumPy, Matplotlib

## Research Questions

1. Can competing drives produce more robust exploration strategies than single-objective RL?
2. How do different drive weightings affect the emergence of aligned vs. exploitative behaviors?
3. What behavioral patterns emerge when curiosity conflicts with safety constraints?

## Current Progress

- Implemented base multi-drive reward framework
- Testing across CartPole, MountainCar, and LunarLander environments
- Analyzing emergent exploration behaviors and safety trade-offs
- Documenting patterns where drive conflicts lead to interesting behavioral dynamics

---

**Status:** In Progress | **Timeline:** Aug 2025 – Ongoing  
