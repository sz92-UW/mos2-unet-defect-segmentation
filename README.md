# U-Net Defect Segmentation for MoS2 Microscopy Images

## Overview
This project applies a PyTorch U-Net model to segment defect regions in MoS2 microscopy images. The workflow includes image preprocessing, mask generation, training and validation splitting, data augmentation, model training, and IoU-based performance evaluation.

## Motivation
Defect identification is important for understanding the quality and behavior of two-dimensional materials. This project uses deep learning and computer vision methods to support materials image analysis.

## Methods
- Python
- PyTorch
- U-Net image segmentation
- Microscopy image preprocessing
- Data augmentation
- Intersection-over-Union evaluation

## Results
The model was trained to identify defect regions in MoS2 microscopy images. Training records for different epoch settings are included, along with IoU comparison results and visual examples of predicted defect masks.

## Skills Demonstrated
- Deep learning for materials images
- Computer vision
- PyTorch model development
- Scientific data preprocessing
- Materials informatics
- Model evaluation and visualization

## Repository Structure
- `mos2_U-Net_defect_segmentation.ipynb`: cleaned Jupyter notebook for the full U-Net defect segmentation workflow
- `comparison_defect_iou.png`: summary figure comparing defect IoU performance across different training settings
- `training_records/`: training history plots and result summary JSON files from model training
- `key_results/`: core visual segmentation results, including original images, ground-truth masks, and predicted defect masks

## Notes
This repository is a cleaned academic project summary. Private course materials, large raw datasets, and unnecessary temporary files are not included.
