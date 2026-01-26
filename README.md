# Clinix-Link-Medical-NLP
A BioBERT-based Transformer pipeline for semantic extraction of clinical markers from unstructured pediatric and cardiac narratives.

##  Project Overview
Clinix-Link is a research-grade NLP pipeline designed to extract early-diagnostic biomarkers from unstructured clinical text. Developed during a period of research refinement (2025-2026), this project addresses the semantic limitations of traditional biometric data by utilizing Neural Transformer architectures.

##  Key Features
- **Model:** Deploys `d4data/biomedical-ner-all` (BioBERT-based) for high-precision Clinical Entity Recognition.
- **Linguistic Logic:** Utilizes WordPiece tokenization to maintain semantic accuracy for complex medical morphemes.
- **Domain Focus:** Specifically tuned for Pediatric (Vitamin D deficiency) and Cardiovascular (Hypertensive Heart Disease) narratives.

##  Results
The pipeline generates a Semantic Confidence Map (Heatmap) to visualize the AI's certainty in identifying clinical markers, achieving up to 1.000 confidence in acute diagnostic detection.
