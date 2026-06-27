# Multi-Identity Multimodal Deepfake Detection

A research project proposing a speaker-aware multimodal framework for deepfake detection in two-person videos. The model combines visual artifact analysis, audio-visual coherence modeling, and identity-aware cross-modal attention to improve deepfake detection in multi-identity scenarios.

## Overview

Traditional deepfake detection methods primarily focus on single-subject videos. This project addresses the more challenging problem of detecting deepfakes in videos containing two individuals, where correctly associating speakers with faces is essential.

The proposed framework integrates:

* MobileNetV3 for visual feature extraction
* Bidirectional LSTM for temporal modeling
* Speaker-face alignment module
* Identity-aware cross-modal attention
* Multimodal fusion of visual and audio cues

## Repository Structure

```
├── 2_people_detection_in_videos.ipynb
├── DeepFake Identification.ipynb
├── DeepFake Detection.pdf
└── README.md
```

## Dataset

Experiments were conducted using a curated subset of the Deepfake Detection Challenge (DFDC) dataset containing two-person video clips.

## Results

* Balanced Accuracy: 65.5%
* AUC: 72.3%

The proposed approach demonstrates improved performance over baseline methods that do not explicitly model speaker-face associations in multi-person videos.

## Research Paper

- **[Research Paper](Research_Paper.pdf)**
The complete methodology, experiments, and analysis are available in the accompanying research paper included in this repository.

## Author

**Syed Bilal Hassan**
Department of Artificial Intelligence
FAST National University of Computer and Emerging Sciences, Islamabad
