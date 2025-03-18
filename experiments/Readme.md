# Utility Functions

## Overview
Common utilities and helper functions for medical image and video processing.

## Structure
```
utils/
│
├── preprocessing/
├── augmentation/
├── visualization/
└── evaluation/
```

## Components

### Preprocessing
- DICOM handling
- Normalization
- Standardization
- Filtering

### Augmentation
- Medical-specific augmentations
- Realistic transformations
- Domain adaptation

### Visualization
- Medical image plotting
- Segmentation visualization
- Analysis result display

### Evaluation
- Medical metrics
- Performance evaluation
- Statistical analysis

## Usage Examples
```python
# Preprocessing
from utils.preprocessing import DicomPreprocessor

preprocessor = DicomPreprocessor()
processed_image = preprocessor.process("scan.dcm")

# Visualization
from utils.visualization import MedicalVisualizer

visualizer = MedicalVisualizer()
visualizer.plot_results(original, prediction, ground_truth)
```
