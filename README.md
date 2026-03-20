# PneumoEdge Research

Scientific research repository for the DiagnoAI Global diagnostic platform.

This repository contains the scientific documentation, experimental results,
and clinical evidence underpinning the PneumoEdge edge AI system.

## Research Summary

This work developed and validated computationally efficient deep learning
models for automated pneumonia detection in chest X-rays, optimised for
deployment in low-resource clinical settings.

**Key results:**
- Quantised Xception: 97.12% accuracy, AUROC 0.9934, 21.61 MB (paediatric)
- Quantised EfficientNetB4: 80.94% accuracy, AUROC 0.856, 18.59 MB (adult)
- Sub-second inference on Raspberry Pi 4B
- 74–91% model size reduction via quantisation

## Repository Structure
```
paper/          — MSc dissertation (Kingston University, 2025)
experiments/    — Inference validation tests and reproducibility notes
results/        — Benchmark results and performance comparisons
figures/        — Grad-CAM visualisations and architecture diagrams
```

## Publication Status

Extended work submitted to Radiology: Artificial Intelligence (Rad:AI).
Currently under peer review.

## Datasets

- Mendeley Paediatric: DOI 10.17632/rscbjbr9sj.3
- NIH ChestX-ray14: https://nihcc.app.box.com/v/ChestXray-NIHCC

## Citation
```
@mastersthesis{konadu2025pneumonia,
  title={AI-Powered Pneumonia Detection in Low Resource Settings},
  author={Konadu, Evans},
  school={Kingston University},
  year={2025},
  supervisor={Makris, Dimitrios}
}
```

## Research Team

- Evans Konadu — Primary Researcher
- Professor Dimitrios Makris — Supervisor, Kingston University

## Clinical Scope

This repository currently focuses on **binary pneumonia detection only**.

Multi-disease models are under research and will be introduced
after clinical validation of the primary system.
