# Persian_Garden_Segmentation_Analysis
Deep learning–based semantic segmentation of Persian garden images (Fin Garden, Kashan) using U-Net.

# Persian Garden Segmentation Analysis

This repository contains a deep learning–based semantic segmentation project focusing on
**Persian garden landscapes**, with a case study of **Fin Garden, Kashan (Iran)**.

The project applies a **U-Net architecture (PyTorch)** to segment garden elements from street-level
and landscape photographs.

## Objectives
- Develop a semantic segmentation model for Persian garden imagery
- Analyze spatial components such as vegetation, water, and built elements
- Support urban morphology and landscape perception research

## Classes
The annotated dataset includes the following classes:
1. Trees
2. Buildings
3. Sky
4. Steps
5. Cover Plants
6. Water

## Dataset
- Images are manually annotated using **Roboflow**
- Current dataset size: ~50 images (target: 100 images)
- Single-site case study: **Fin Garden, Kashan**

## Methods
- Framework: **PyTorch**
- Model: **U-Net**
- Loss functions: Dice / Cross-Entropy (to be finalized)
- Evaluation metrics: IoU, Dice coefficient

## Repository Structure
