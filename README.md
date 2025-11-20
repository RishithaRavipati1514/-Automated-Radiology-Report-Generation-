# -Automated-Radiology-Report-Generation-

Project Overview:
This mini-project implements an AI system that automatically generates radiology reports from chest X-ray images using transformer-based architectures. The approach combines a Vision Transformer (ViT) or BioMedCLIP encoder for feature extraction with a Transformer/MiniLM decoder for generating clinical text.
The goal is to assist radiologists by producing faster, accurate, and reliable medical reports.


Abstract:
This work presents an AI-driven system for generating radiology reports from chest X-rays using transformer models. The proposed TrMRG framework uses a Vision Transformer (ViT) encoder and MiniLM decoder to capture spatial features and long-term dependencies. The system is evaluated on the IU Chest X-ray dataset using BLEU, METEOR, and ROUGE-L metrics.
To enhance medical image–text alignment, BioMedCLIP is integrated as a domain-specific encoder. Domain pretraining, optimized hyperparameters, and experimentation with OpenAI-based decoders improve fluency and accuracy. The project aims to support radiologists by delivering higher-quality automated reporting.


Understanding BioMedCLIP:
BioMedCLIP learns both medical images and medical text together.
It creates matching embeddings (“fingerprints”) for:
->chest X-ray images
->corresponding clinical descriptions
Images and reports with similar meaning get similar vector representations, helping the model generate more accurate medical text.
