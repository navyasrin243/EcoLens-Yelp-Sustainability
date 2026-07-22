# EcoLens: Hybrid DistilBERT–LightGBM Framework for Sustainability Analysis

EcoLens is a hybrid NLP framework that automatically extracts sustainability-related insights from Yelp reviews using weak supervision and deep language models.

## Problem Statement
Manual analysis of sustainability feedback in online reviews is inefficient and does not scale. This project proposes an automated solution using NLP.

## Methodology
- Yelp Review dataset (200K samples)
- Weak supervision for label generation
- DistilBERT for semantic embeddings
- LightGBM for multi-class classification
- GPU acceleration using Google Colab

## Classes
- eco_practices
- sustainable_operations
- clean_energy
- waste_management
- general

## Results
- Overall accuracy: ~74%
- Strong performance on majority classes
- Clean energy class is challenging due to limited samples

## Tech Stack
- Python
- HuggingFace Transformers
- PyTorch
- LightGBM
- Scikit-learn

## How to Run
```bash
pip install -r requirements.txt
python train.py
```

## Publication
This work was published as a research paper — *EcoLens: Hybrid DistilBERT–LightGBM Framework for Sustainability Analysis* — at NCRTAD 2025.

📄 [View Certificate](ecolens-certificate.pdf.pdf)
