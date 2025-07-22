# Formal Specification and Verification of Rule-Based AI Systems Using Event-B

This repository contains the Event-B models and verification artifacts associated with the paper:

**Formal Specification and Verification of Rule-Based Artificial Intelligence Systems Using Event-B**

> Trinh Thanh Binh, et al. (2025)  
> Submitted to *Journal of Systems and Software*.

## Overview

This project demonstrates a formal verification approach for rule-based AI (RB-AI) systems using the Event-B formal method and the Rodin platform. It provides a stepwise refinement framework to detect structural (conflicts, redundancies) and semantic (invariant violations, livelocks) issues in RB-AI rule sets.

The case study **SmartAir**, a rule-based fan controller, is used to illustrate the modeling process and automated proof obligations.

## Repository Contents

- `/models/` — Event-B machine and context files, organized by refinement steps:
  - `RB_AI_Abstract` — Static structure and initial behavior.
  - `RB_AI_Refine_Struct` — Structural checks (conflict, redundancy).
  - `RB_AI_Refine_Semantic` — Semantic monitoring (invariant, livelock).
- `/figures/` — Model diagrams exported from Rodin.
- `/report/` — Optional analysis outputs or proof statistics.

## Rodin Platform

To explore or verify the models, install the [Rodin Platform](https://www3.hhu.de/stups/rodin.html). All proof obligations (POs) were automatically discharged in version 3.8

## Link to Publication

📄 The corresponding research article is available here:  
[https://doi.org/xxxxx](https://doi.org/xxxxx) *(update when available)*

## Citation

If you use this project or models in your work, please cite:

