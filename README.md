# Final-Year-Project
# Cloud-based Bacterial Colonies Identification Application
This project is an AI-powered system designed to identify and classify bacterial colonies from high-resolution images. It leverages deep learning models to automate the detection of four major types of bacteria commonly found in clinical, food, and environmental samples.
# Project Overview
Traditional bacterial identification methods can be time-consuming and require expert analysis. This application automates the process using a cloud-deployable AI model trained on a custom dataset of bacterial colony images. It uses Convolutional Neural Networks (CNNs) such as EfficientNetB3 and ResNet50 for high-accuracy classification.
# Dataset
The dataset consists of **4,000 annotated images** of bacterial colonies grown on various agar media. Each class has 1,000 images:
- E. coli
- Salmonella
- Enterococcus
- Staphylococcus

Images were preprocessed and augmented to improve model generalization.

# Model Architecture

We trained and evaluated the following CNN architectures:

- `EfficientNetB3` – for lightweight yet powerful performance
- `ResNet50` – for robust deep feature extraction

All models were fine-tuned using transfer learning and trained with categorical cross-entropy loss.
