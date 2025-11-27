# softskills-annotation-study
This repository contains the public artifacts associated with the paper: "When LLMs Play Annotator: Human–LLM Agreement in Soft Skills Classification", submitted to EGC2026

Because the underlying data and code belong to Central Test and cannot be released,
this repository provides **transparent documentation** of the experimental setup:

### Contents
- **Prompts**: LLM system and few-shot prompts used for annotation.
- **Results**: CSV files with agreement metrics (Krippendorff’s α, F1, κ, Hamming Loss, coverage, semantic similarity).
- **Pseudocode**: High-level descriptions of the annotation and evaluation pipeline.
- **Public Notebook**: `analysis_public.ipynb` reproduces all plots and tables from the paper using the exported result files.

### Non-public components
Due to confidentiality constraints, the following cannot be released:
- The proprietary soft-skill referential
- Raw expressions and annotations
- Internal feature extraction or pipeline code

### Purpose
The goal of this repository is to ensure **methodological transparency** and
to enable reviewers to inspect the prompts, evaluation logic, and summary outputs
used in the paper.
