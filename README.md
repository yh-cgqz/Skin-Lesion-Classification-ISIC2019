# Skin-Lesion-Classification-ISIC2019
This project explores deep learning approaches for automated skin lesion classification using the ISIC 2019 Dataset. The goal is to assist in early melanoma detection by leveraging a hybrid MobileNet + Vision Transformer (ViT) model, and comparing its performance against other state-of-the-art CNNs including ResNet-50, InceptionV3, and EfficientNetB0.

The project covers data preprocessing, model development, evaluation using clinical metrics, and explainability using Grad-CAM heatmaps.

## Key Features
- Multi-class classification on 7 skin lesion types (MEL, NV, BKL, etc.)
- Hybrid MobileNet + Vision Transformer (ViT) model architecture
- Transfer learning with ResNet-50, InceptionV3, EfficientNetB0
- Robust preprocessing: resizing, normalization, augmentation
- Tackles class imbalance using computed class weights
- Evaluation: Accuracy, F1-Score, AUC-ROC, Confusion Matrix
- Model interpretability via Grad-CAM heatmaps

## Dataset
https://challenge.isic-archive.com/data/#2019
Total Images: ~25,000 dermoscopic images across 7 diagnostic categories.
Includes metadata and ground-truth CSVs.

## Disclaimer
This model is for academic and research purposes only. It is not intended for clinical diagnosis. Always consult certified medical professionals for diagnosis and treatment.
