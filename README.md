# Multimodal Pathology Transformer

A small research-oriented proof-of-concept exploring multimodal learning with Transformer architectures for computational pathology.

## Project Goal

The project demonstrates an end-to-end workflow for combining **pathology image representations** and **molecular data** using PyTorch and Transformer-based multimodal fusion.

The primary goal is to gain and demonstrate hands-on experience with:

* real biomedical datasets
* pathology image representations
* RNA expression data
* multimodal representation learning
* PyTorch model development
* Transformer-based fusion

## Dataset and Scope

The project uses a small cohort of **three TCGA-BRCA patients** with both pathology and molecular data.

This intentionally small cohort is a practical compromise because whole-slide pathology images are extremely large. The priority is to demonstrate the complete technical workflow rather than build a clinically meaningful predictive model.

Therefore, model performance and generalization should **not** be interpreted as clinically or statistically meaningful.

## Approach

```text
TCGA-BRCA
    │
    ├── Pathology WSI → image representations
    │
    └── RNA expression → molecular representations
                 │
                 ↓
        Multimodal Transformer
                 │
                 ↓
             Prediction
```

## Project Structure

```text
data/        Dataset-related files
notebooks/   Exploration and experiments
src/         Reusable Python code
results/     Experimental results
```

## Current Stage

* TCGA-BRCA cohort exploration completed
* Matched pathology and RNA data identified
* Dataset scope reduced to a three-patient proof-of-concept
* Multimodal pipeline under development

