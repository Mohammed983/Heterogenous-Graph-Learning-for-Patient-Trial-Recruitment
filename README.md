# Heterogenous-Graph-Learning-for-Patient-Trial-Recruitment

## Overview
Built a graph-based machine learning system to match patients with relevant clinical trials by integrating real-world healthcare datasets.

## Problem
Clinical trial matching is inefficient due to unstructured eligibility criteria and fragmented patient data. This project explores using graph learning to model relationships between patients, diseases, and trials.

## Approach
- Processed datasets (MIMIC-IV, ClinicalTrials.gov)
- Standardized disease representation using embeddings (PubMedBERT)
- Constructed a heterogeneous graph:
  - Nodes: patients, diseases, trials
  - Edges: has_disease, eligible_for
- Trained Graph Neural Networks (HGT) for link prediction
- Applied negative sampling and ranking-based evaluation

## My Contributions
- Built data preprocessing and embedding pipeline
- Designed graph schema and relationships
- Implemented model training and evaluation pipeline
- Analyzed performance using ranking metrics (Top-K matching)

## Tech Stack
Python, PyTorch Geometric, PubMedBERT, Graph Neural Networks

## Results
- Demonstrated effective patient-trial matching using learned representations
- Improved ranking quality for relevant trials (Top-K evaluation)

## Limitations & Future Work
- Expand to include medications and procedures
- Improve generalization across unseen datasets
- Integrate into real-time recommendation systems

## Note
This project was developed as part of a team effort and the original repository is private.
