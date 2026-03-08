# DLF-Net: LiDAR Point Cloud Segmentation Network Based on Dual-Domain Learning and Fusion for Railway Scenes

## Introduction
This repository will contain the official implementation of DLF-Net, a LiDAR 
point cloud segmentation network based on dual-domain learning and fusion, 
designed for railway scene understanding.

DLF-Net integrates three specialized modules:
- **FDL**: Axial Fine-Grained Domain Learning Module, which employs gated axial 
  convolution units to extract fine-grained features from three orthogonal planes.
- **HDM**: Multi-Sequence Holistic Domain Modeling Module, which captures 
  long-range dependencies through space-filling curve transformations combined 
  with multi-scale partitioning strategies.
- **CFF**: Cross-Domain Feature Fusion Module, which performs bidirectional 
  interaction between fine-grained and holistic features through cross-attention 
  mechanisms.

## Dataset
This repository will also include the **RailPoints-V2** dataset, an extension of 
our RailPoints dataset for railway scene LiDAR point cloud segmentation. 
RailPoints-V2 consists of 374 frames covering 35 kilometers of railway scenarios, 
annotated into six semantic categories: Terrain, Rail, Pedestrian, Vegetation, 
Artifact, and Obstacle.

## Code and Dataset Availability
The source code and RailPoints-V2 dataset will be released upon acceptance of 
this manuscript.
