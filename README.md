# Emotion Recognition & Face Detection  
**TDDE70 – Deep Learning Project**

## Overview
This project implements a combined system for **face detection** and **emotion classification** using deep learning.

The pipeline:
1. Detect faces using a ResNet-50 based model.
2. Classify detected faces into 8 emotion classes.

Transfer learning was used to handle computational constraints and limited dataset size.

## Datasets
- AffectNet (subset ~16k images, 8 emotion classes)
- Face Detection Dataset and Benchmark (patch-based training)

## Models
### Face Detection
- ResNet-50 (frozen layers)
- Patch-based classification
- Validation accuracy: **90%**

### Emotion Classification
- ResNet-50 backbone
- Dropout + BatchNorm + Linear layer
- Validation accuracy: **41.6%**
- Training accuracy: **97.3%**

## Key Challenges
- Imbalanced datasets
- Hardware limitations
- Difficulty of accurate emotion recognition

## Presentation
Project slides available here:  
👉 [View PowerPoint Presentation](./TDDE70.pptx)

