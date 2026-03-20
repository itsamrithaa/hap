# HAP Circuit Discovery Visualizer 🤖🔍

> Official Visualizer for: *"Discovering Transformer Circuits via a Hybrid Attribution and Pruning Framework"*

This repository contains the interactive visualization platform for the **HAP (Hybrid Attribution and Pruning) Framework**. This tool was designed to bridge the gap between complex mechanistic interpretability research and human-readable circuit analysis, specifically highlighting the efficiency gains and faithfulness of the HAP model.

## Overview
Interpreting Large Language Models (LLMs) requires identifying "circuits"—sparse subnetworks responsible for specific behaviors. Existing methods suffer from a fundamental trade-off: **Attribution Patching** is fast but unfaithful, while **Edge Pruning** is faithful but computationally expensive.

**HAP** breaks this trade-off by using attribution to identify high-potential subgraphs and then applying pruning to extract faithful circuits.

### Key Results:
* **46% Faster:** Significantly reduces runtime compared to baseline edge pruning algorithms.
* **Superior Faithfulness:** Preserves critical cooperative components (like S-inhibition heads in the IOI task) that standard attribution methods often prune at high sparsity.
* **Scalable:** Effectively improves the scalability of mechanistic interpretability research to larger, industrial-sized models.

---

## Research & Credits
This visualizer is based on the research paper:
**"Discovering Transformer Circuits via a Hybrid Attribution and Pruning Framework"**

### Authors:
* **Hao Gu**
* **Vibhas Nair**
* **Amrithaa Ashok Kumar** 
* **Jayvart Sharma**
* **Ryan Lagasse** 

### Citation & Links:
* **arXiv:** [2510.03282 [cs.LG]](https://doi.org/10.48550/arXiv.2510.03282)
* **Venue:** Accepted to **NeurIPS 2025** Workshop on Mechanistic Interpretability and the **NeurIPS 2025** Workshop on New Perspectives in Graph Machine Learning.
* **Original Research Code:** [Link to Paper Code Will Be Updated Here Soon]

---

## Getting Started
To run the visualizer locally on your machine

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[your-username]/hap-circuit-discovery-visualization.git
