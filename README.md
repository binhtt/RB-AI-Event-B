# Formal Specification and Verification of Rule-Based AI Systems Using Event-B

This repository contains the Event-B models, refinement machines, and verification artifacts associated with the research paper:

**Formal Specification and Verification of Rule-Based Artificial Intelligence Systems Using Event-B**

> Thanh-Binh Trinh and Ninh-Thuan Truong  
> Manuscript currently under review at PeerJ Computer Science.

---

## Overview

This project presents a formal modeling and verification framework for Rule-Based Artificial Intelligence (RB-AI) systems using the Event-B formal method and the Rodin platform.

The framework supports:

- Formal specification of rule-based behaviors
- Rule evaluation and action execution modeling
- Conflict detection
- Redundancy detection
- Invariant preservation
- Livelock detection and recovery
- Automated proof obligation verification

The repository also includes the **SmartAir** case study, a rule-based smart fan controller used to demonstrate the verification workflow.

---

## Repository Structure

```text
models/
├── RB-AI-Abstract-Context.buc
├── RB-AI-Abstract-Machine.bum
├── RB-AI-Refine-Context.buc
├── RB-AI-Refine-Machine.bum
├── *.bpo
├── *.bpr
├── *.bps
└── *.bcm
