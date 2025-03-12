# Transfer Learning for Image Classification

## Project Overview
- Explore the effectiveness of transfer learning in image classification.
- Compare pre-trained models (VGG and ResNet18) on the Intel Image Classification dataset.
- Fine-tune models using different strategies.
- Evaluate performance using accuracy, F1-score, and confusion matrices.
- Understand how architectural differences and fine-tuning approaches impact performance.

## Data Preparation
- **Dataset:** Intel Image Classification (available on Kaggle)
- **Classes:** buildings, forest, glacier, mountain, sea, street
- Load data using PyTorch's ImageFolder or a custom dataset class.
- Split into train (70%), validation (15%), and test (15%) sets.
- Visualize sample images from each class.
- Apply necessary data augmentation.

## Model Fine-Tuning
- Fine-tune the VGG and ResNet18 models.
- Experiment with various fine-tuning strategies (e.g., freezing layers, adjusting learning rates).

## Evaluation & Analysis
- Evaluate models using accuracy, F1-score, and confusion matrices.
- Document experiments in a Jupyter Notebook with code, visualizations, and structured analysis.
