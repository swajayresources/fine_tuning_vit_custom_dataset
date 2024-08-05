# Fine-tuning a Vision Transformer Model With a Custom Biomedical Dataset
This guide outlines the process for fine-tuning a Vision Transformer (ViT) model on a custom biomedical dataset. It includes steps for loading and preparing the dataset, setting up image transformations for different data splits, configuring and initializing the ViT model, and defining the training process with evaluation and visualization tools.

# Dataset Info
The custom dataset is hand-made, containing 780 images with 3 classes (benign, malignant, normal).

# Model Info
The model we fine-tune will be Google's "vit-large-patch16-224". It is trained on ImageNet-21k (14M images, 21.843 classes), and fine-tuned on ImageNet 2012 (1M images, 1.000 classes) at resolution 224x224. Google has several other ViT models with different image sizes and patches.
