# ResNet50-Vision-Transformer-for-GI-Pathology-Detection

# Automated Gastrointestinal Disease Detection using Endoscopic Images

This repository contains the implementation and benchmarking of **ResNet-50** and **Vision Transformer (ViT)** models for multi-class classification of gastrointestinal (GI) diseases using the [Kvasir Dataset](https://datasets.simula.no/kvasir/). The project aims to compare the performance of CNN-based and transformer-based architectures in medical image analysis.

## 📌 Key Features
- **Multi-class classification** of 8 GI conditions (e.g., polyps, ulcerative colitis, esophagitis).
- **Benchmarking** of ResNet-50 (CNN) vs. Vision Transformer (ViT).
- **Comprehensive evaluation**: Accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.
- **Computational complexity analysis** (parameters, MACs, memory usage).

## 📊 Results Summary
| Model       | Test Accuracy | Params   | MACs     | Best-Performing Class          |
|-------------|--------------|----------|----------|--------------------------------|
| ResNet-50   | 93.27%       | 23.5M    | 4.13 GMac| `normal-pylorus` (100% accuracy)|
| ViT         | 89.18%       | 85.8M    | 17.61 GMac| `normal-cecum` (100% accuracy) |

For detailed results, see the [Results Documentation](RESULTS.md) or the project paper (link TBD).

---

## 🛠️ Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/gastrointestinal-disease-detection.git
   cd gastrointestinal-disease-detection


   @misc{akwasiasare2024gidetection,
  author = {Akwasi Asare},
  title = {Automated GI Disease Detection using ResNet-50 and Vision Transformers},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{(https://github.com/nasare34/ResNet50-Vision-Transformer-for-GI-Pathology-Detection)}}
}
