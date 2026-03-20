# Inference Benchmarks

## Binary Classification Performance (Pre-Quantisation)

| Model | Dataset | Accuracy | Sensitivity | Specificity | AUROC | Size |
|-------|---------|----------|-------------|-------------|-------|------|
| Xception | Mendeley | 96.96% | 96.92% | 97.01% | 0.9933 | 82.08 MB |
| EfficientNetB4 | NIH | 86.10% | 78.91% | 88.99% | 0.8986 | 208.32 MB |
| Nuclear Ensemble | Mendeley | 96.79% | 96.67% | 97.01% | 0.9915 | 300.74 MB |

## Binary Classification Performance (Post-Quantisation)

| Model | Dataset | Accuracy | Sensitivity | Specificity | AUROC | Size | Inference |
|-------|---------|----------|-------------|-------------|-------|------|-----------|
| Xception | Mendeley | 97.12% | 97.69% | 96.15% | 0.9934 | 21.61 MB | 550.76 ms |
| EfficientNetB4 | NIH | 80.94% | 72.66% | 84.28% | 0.856 | 18.59 MB | 232.69 ms |

CheXNet (Stanford DenseNet-121 baseline): AUROC 0.768
EfficientNetB4 exceeds CheXNet by 17% on AUROC.
