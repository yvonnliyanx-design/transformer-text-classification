# Transformer-Based Text Classification

This project explores transformer-based models for multi-class text classification using the 20 Newsgroups dataset.

The project compares BERT, RoBERTa, and DistilBERT under different experimental settings, including preprocessing and data augmentation strategies.

## Key Experiments
- Baseline transformer fine-tuning
- Stopword removal & stemming analysis
- Synonym-based data augmentation
- Attention-based interpretability analysis
- ONNX model export for deployment

## Results
- BERT achieved the strongest overall performance
- Traditional preprocessing slightly reduced transformer performance
- Data augmentation improved macro-F1 and generalization

## Tools
Python | PyTorch | Hugging Face Transformers | Scikit-learn | ONNX
