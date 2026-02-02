# Computer Vision Course - 7th Semester

**Student**: Muhammad Abdullah Awan  
**Roll Number**: 2022-SE-08  
**University**: The University of Azad Jammu and Kashmir  
**Semester**: 7th  
**Date**: February 2026

---

## 📁 Repository Structure

This repository contains all coursework for the Computer Vision course, organized into the following folders:

```
Computer_Vision/
├── Assignment/              # Individual Assignment Work
├── Quiz/                    # Quiz 1 (Individual)
├── Quiz2/                   # Quiz 2 (Individual)
└── computer_vision_project/ # Team Project
```

---

## 📂 Folder Descriptions

### 1. 📝 Assignment (Individual Work)

**Student**: Muhammad Abdullah Awan (2022-SE-08)

Contains individual assignment work focused on hybrid image creation and frequency domain image processing.

**Contents**:
- `hybrid_image_assignment.ipynb` - Hybrid image generation using frequency domain techniques

**Topics Covered**:
- Gaussian filtering
- Frequency domain processing
- Low-pass and high-pass filtering
- Hybrid image creation

---

### 2. 📋 Quiz (Individual Work)

**Student**: Muhammad Abdullah Awan (2022-SE-08)

Contains Quiz 1 work on dynamic slip cropping and processing.

**Contents**:
- `Dynamic_Slip_Cropping.ipynb` - Automated slip detection and cropping
- `cropped_slips/` - Output folder for processed images

**Topics Covered**:
- Image preprocessing
- Object detection
- Dynamic cropping techniques
- Batch image processing

---

### 3. 📋 Quiz2 (Individual Work)

**Student**: Muhammad Abdullah Awan (2022-SE-08)

Contains Quiz 2 work on dollar bill value detection using deep learning.

**Contents**:
- `Dollar_Bill_Detection_Quiz2.ipynb` - CNN-based dollar bill classifier

**Topics Covered**:
- Train/Test data splitting
- CNN architecture design
- Transfer learning with EfficientNetB0
- Image classification
- Model evaluation and accuracy testing

**Key Requirements Met**:
- ✅ Created separate test folder with same structure as training
- ✅ Ensured no overlap between train and test datasets
- ✅ Trained CNN model for multi-class classification
- ✅ Tested accuracy on independent test data

---

### 4. 🎯 computer_vision_project (Team Project)

**Team Members**:
- Muhammad Abdullah Awan (2022-SE-08)
- Umair Imtiza Khokhar (2022-SE-18)
- Awais Ahmed Abbasic (2022-SE-29)

**Project**: ECG Image Digitization - Kaggle Competition

Contains team project work for the PhysioNet ECG Image Digitization Challenge, converting ECG images to digital time-series signals.

**Contents**:
- `README.md` - Detailed project documentation
- `ecg_training.ipynb` - Approach 1: Custom CNN training
- `ecg-testing.ipynb` - Approach 1: Testing and submission
- `open-ecg-digitizerv6.ipynb` - Approach 2: Multi-stage pipeline (Best Performance)

**Project Overview**:
- **Competition**: PhysioNet ECG Image Digitization on Kaggle
- **Task**: Convert 12-lead ECG images to digital waveforms
- **Evaluation Metric**: Signal-to-Noise Ratio (SNR)

**Approaches Compared**:

| Approach | Kaggle Score | Description |
|----------|--------------|-------------|
| Approach 1: Custom CNN | 0.08 | Simple end-to-end learning |
| Approach 2: Multi-stage Pipeline | 17.1 | Pre-trained models + domain knowledge |

**Key Learnings**:
- Multi-stage processing outperforms end-to-end learning for complex tasks
- Domain knowledge integration is crucial for medical imaging
- Transfer learning significantly improves performance
- Task decomposition (normalization → grid detection → signal extraction) is effective

---

## 🎓 Course Topics Covered

### Image Processing Fundamentals
- Frequency domain analysis
- Gaussian filtering
- Image transformations
- Preprocessing techniques

### Computer Vision Techniques
- Object detection and cropping
- Image segmentation
- Feature extraction
- Grid and keypoint detection

### Deep Learning for Vision
- Convolutional Neural Networks (CNN)
- Transfer learning (EfficientNetB0, MobileNetV2, ResNet)
- Data augmentation strategies
- Model training and optimization
- Multi-stage pipeline architectures

### Model Evaluation
- Train/Test splitting strategies
- Accuracy metrics
- Confusion matrices
- Classification reports
- SNR (Signal-to-Noise Ratio) for signal processing

---

## 📊 Work Classification

| Work Type | Project/Quiz | Student(s) | Folder |
|-----------|-------------|------------|---------|
| Individual | Assignment | Abdullah (Roll 8) | `Assignment/` |
| Individual | Quiz 1 | Abdullah (Roll 8) | `Quiz/` |
| Individual | Quiz 2 | Abdullah (Roll 8) | `Quiz2/` |
| Team | Project | Abdullah, Umair, Awais | `computer_vision_project/` |

---

## 🛠️ Technologies Used

### Programming Languages
- Python 3.x

### Libraries & Frameworks
- **Deep Learning**: TensorFlow, Keras, PyTorch
- **Computer Vision**: OpenCV, PIL/Pillow
- **Scientific Computing**: NumPy, SciPy
- **Data Manipulation**: Pandas
- **Visualization**: Matplotlib, Seaborn
- **Image Processing**: scikit-image, Albumentations
- **Pre-trained Models**: timm (PyTorch Image Models)

### Development Environment
- Google Colab (for GPU acceleration)
- Jupyter Notebook
- VS Code

---

## 📈 Performance Highlights

### Quiz 2: Dollar Bill Detection
- Successfully implemented train/test splitting
- Achieved high accuracy using transfer learning
- Proper data augmentation and model evaluation

### Team Project: ECG Digitization
- **Best Kaggle Score**: 17.1 SNR
- **213x improvement** over naive approach
- Demonstrated importance of domain-specific design
- Multi-stage pipeline outperformed end-to-end learning

### Assignment: Hybrid Images
- Successful frequency domain manipulation
- Proper implementation of Gaussian filters
- Created perceptually interesting hybrid images

---

## 📝 Notes

- **Individual Work**: Assignments and quizzes are completed independently by Muhammad Abdullah Awan
- **Team Work**: The ECG project is collaborative team effort
- **Code Quality**: All notebooks include detailed comments and explanations
- **Reproducibility**: Random seeds set for consistent results
- **Documentation**: Comprehensive README files in project folders

---

## 📞 Contact

**Muhammad Abdullah Awan**  
Roll Number: 2022-SE-08  
Course: Computer Vision (7th Semester)  
University: The University of Azad Jammu and Kashmir

---

## 📄 License

Educational coursework for university requirements.

---

**Last Updated**: February 2, 2026
