# Model Architectures

## Overview
Collection of deep learning models for medical image and video analysis.

## Structure
```
models/
│
├── classification_models/
├── segmentation_models/
└── detection_models/
```

## Components

### Classification Models
- ResNet adaptations
- DenseNet variants
- Vision Transformer implementations

### Segmentation Models
- U-Net architectures
- DeepLab variants
- Attention U-Net

### Detection Models
- YOLO adaptations
- RetinaNet implementations
- Faster R-CNN variants

## Usage Examples
```python
# Load Classification Model
from models.classification_models import MedicalResNet

model = MedicalResNet(num_classes=5)
model.load_weights("pretrained_weights.pth")

# Initialize Segmentation Model
from models.segmentation_models import MedicalUNet

segmenter = MedicalUNet(in_channels=1, out_channels=2)
```
