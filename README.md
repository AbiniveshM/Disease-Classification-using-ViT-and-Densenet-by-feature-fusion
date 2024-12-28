Disease Classification using Vision Transformers (ViT) and DenseNet by Feature Fusion

Overview

This project implements a disease classification system leveraging Vision Transformers (ViT) and DenseNet models. By employing a novel feature fusion approach, it combines the strengths of both architectures to enhance prediction accuracy on medical datasets. This method ensures robust and reliable performance in classifying diseases.


Features

Vision Transformers (ViT): Extracts global features with self-attention mechanisms.

DenseNet: Captures local features efficiently through densely connected layers.

Feature Fusion: Integrates features from both models to improve overall performance.

High Accuracy: Ensures reliable classification by leveraging complementary strengths of both architectures.


Dataset

The system uses a publicly available medical dataset for disease classification. Ensure you have the dataset downloaded and preprocessed before running the code.

Link - (https://ieee-dataport.org/documents/chest-x-ray-images-multiple-diseases)


Requirements

Python 3.8 or above

PyTorch

TensorFlow/Keras (if applicable)

NumPy

Matplotlib

Scikit-learn


Install dependencies using:

pip install -r requirements.txt


Model Architecture

Vision Transformer (ViT): Captures global relationships in the image.

DenseNet: Provides local feature extraction.

Feature Fusion: Merges ViT and DenseNet features for enhanced decision-making.
