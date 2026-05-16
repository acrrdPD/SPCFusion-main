# SPCFusion

### Code for SPCFusion: Infrared and Visible Image Fusion with Semantic-Aware Perception

Paper | Code | Models

SPCFusion provides the implementation of our infrared and visible image fusion framework. The project contains core modules for multi-scale feature extraction, infrared-visible feature fusion, semantic segmentation assistance, loss functions, data loading, checkpoint saving, and training/testing option configuration.

> The complete training/testing scripts, pre-trained models, and detailed dataset preparation instructions will be updated after publication.

---

## News

- 2026-05-17 The initial code repository is available.
- Pre-trained models and detailed instructions will be released after publication.

---

## TODOs

- [x] Release initial core code
- [ ] Release full training scripts
- [ ] Release testing scripts
- [ ] Release pre-trained models
- [ ] Release detailed dataset preparation instructions
- [ ] Add paper DOI and BibTeX citation

---

## ✨ Overview

SPCFusion is designed for infrared and visible image fusion. The current code includes:

- A dual-branch encoder for extracting visible and infrared features.
- Multi-scale detail representation blocks with Sobel-based edge enhancement.
- Spatial and channel attention modules for adaptive feature modulation.
- A fusion decoder for reconstructing fused images.
- A segmentation decoder for semantic-aware auxiliary supervision.
- Fusion losses based on intensity, gradient, MS-SSIM, perceptual consistency, and task-related constraints.
- Utility functions for RGB/YCrCb conversion, segmentation visualization, data augmentation, and metric calculation.

---

## ✨ Usage

### 1. Clone this repository and set up the environment

```bash
git clone https://github.com/acrrdPD/SPCFusion-main.git
cd SPCFusion-main
