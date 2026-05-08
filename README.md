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

figures/
└── rodin_verification.png

README.md
LICENSE
```

---

## Main Components

### Abstract Context

Defines the static structure of the RB-AI system, including:

- states
- rules
- actions
- semantic functions

### Abstract Machine

Models generic RB-AI execution behavior, including:

- rule evaluation
- action selection
- state transitions

### Refinement Context

Introduces predicates for:

- conflict detection
- redundancy analysis
- cycle detection

### Refinement Machine

Extends the abstract model with:

- structural verification
- semantic monitoring
- livelock detection
- recovery handling

---

## Requirements

To reproduce the verification results, install:

- Rodin Platform 3.8 or later
- Java 11 or later

Rodin Platform website:

https://www3.hhu.de/stups/rodin.html

---

## How to Import and Verify the Models

1. Open Rodin Platform
2. Create a new Event-B project
3. Import all `.bum`, `.buc`, `.bpo`, `.bpr`, `.bps`, and `.bcm` files
4. Open the Event-B machines and contexts
5. Run the automatic provers in Rodin

All proof obligations (POs) included in the project were automatically discharged in Rodin 3.8.

---

## Verification Summary

The Event-B models verify several important RB-AI correctness properties, including:

- Rule conflict detection
- Rule redundancy elimination
- Invariant preservation
- Livelock detection
- Safe-state recovery

The SmartAir case study demonstrates automated verification of structural and semantic correctness properties in a reactive AI-IoT environment.

---

## Verification Statistics

The Rodin platform automatically generated and discharged all proof obligations associated with the refinement chain.

Verified properties include:

- invariant preservation
- conflict detection
- redundancy elimination
- livelock detection
- recovery correctness

---

## Code and Artifact Availability

All Event-B models and Rodin verification artifacts used in the study are publicly available in this repository for research and reproducibility purposes.

Repository:

https://github.com/binhtt/RB-AI-Event-B

---

## Authors

### Thanh-Binh Trinh
Faculty of Information Systems  
Phenikaa University, Vietnam

### Ninh-Thuan Truong
VNU University of Engineering and Technology, Vietnam

---

## Citation

If you use this repository or the associated Event-B models in your research, please cite:

> Thanh-Binh Trinh and Ninh-Thuan Truong,  
> *Formal Specification and Verification of Rule-Based Artificial Intelligence Systems Using Event-B*,  
> under review at PeerJ Computer Science, 2026.

---

## License

This repository is provided for academic and research purposes.
