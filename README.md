# felfel_resarch_code
# ArtFusionNet: Enhancing Artistic Style Classification

## Overview
This repository contains the MATLAB implementation of **ArtFusionNet**, a framework for artistic style classification that fuses CNN multi-scale feature extraction with Transformer global modeling via an Adaptive Fusion Module (AFM).

## Requirements
- MATLAB R2021a or later
  - Deep Learning Toolbox
  - Image Processing Toolbox

## Dataset
Prepare datasets in the following structure:
datasets/
├── WikiArt/
├── BAM/
├── Painting91/
└── Fallah_artist_dataset/

## Usage

### Training
```matlab
main_train.m

