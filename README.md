# 👁️ Computer Vision & Deep Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![License](https://img.shields.io/badge/License-Academic-green?style=for-the-badge)
![Notebooks](https://img.shields.io/badge/Notebooks-20%2B-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

<br/>

<img src="https://raw.githubusercontent.com/nielitropar/computer-vision/refs/heads/main/assets/Sarwan_Singh.JPG" width="130" style="border-radius: 50%;" alt="Dr. Sarwan Singh"/>

**Dr. Sarwan Singh**, Scientist-D  
*Joint Director, NIELIT Deemed to be University, Main Campus Ropar*

<br/>

[📖 Explore Notebooks](#-curriculum--modules) · [🚀 Quick Start](#-getting-started) · [🛠️ Installation](#installation) · [🤝 Acknowledgments](#acknowledgments)

</div>

---

## 📌 Overview

Welcome to the **Computer Vision & Deep Learning** repository — a comprehensive, hands-on academic resource that takes you from the fundamentals of image processing all the way to state-of-the-art deep learning architectures and edge deployment.

This repository is structured as a **progressive learning curriculum**, carefully organized into thematic modules. Whether you're a beginner taking your first steps into AI, or a practitioner looking to sharpen practical skills in object detection, facial recognition, or semantic segmentation, this resource has you covered.

### ✨ What Makes This Repository Special

| Feature | Details |
|---|---|
| 📓 **20+ Jupyter Notebooks** | Carefully structured, hands-on notebooks covering the full CV spectrum |
| 🎓 **Academic Rigor** | Developed under NIELIT Deemed University's academic framework |
| ☁️ **Cloud-Ready** | All notebooks are fully reproducible on Google Colab — no local setup required |
| 🔬 **Theory + Practice** | Each module pairs conceptual foundations with working code |
| 🏭 **Industry-Standard Tools** | Built with TensorFlow, PyTorch, OpenCV, and Ultralytics (YOLOv8) |
| 📱 **Edge Deployment** | Includes TensorFlow Lite export for mobile and IoT applications |

---

## 📚 Curriculum & Modules

The curriculum is organized into **6 progressive modules**, each building on the last. Start from Module 1 if you are new, or jump to the topic most relevant to your needs.

```
Module 1 → Core CV & CNNs
Module 2 → Object Detection & YOLO
Module 3 → Image Classification
Module 4 → Facial Recognition
Module 5 → Image Segmentation
Module 6 → Transfer Learning & Edge Deployment
```

---

### 1️⃣ Core Computer Vision & Convolutional Neural Networks (CNNs)

> **Goal:** Build a solid foundation in how machines perceive and interpret visual data.

This module begins with the absolute basics of computer vision, progressively introducing deep learning concepts and culminating in a thorough understanding of Convolutional Neural Network (CNN) internals.

| Notebook | Description | Level |
|---|---|---|
| [**Intro to Computer Vision**](https://github.com/nielitropar/computer-vision/blob/main/Intro_to_Computer_Vision.ipynb) | Core CV concepts: image representation, pixel manipulation, filters, and transformations using OpenCV | 🟢 Beginner |
| [**Computer Vision with Deep Learning**](https://github.com/nielitropar/computer-vision/blob/main/Computer_Vision_with_Deep_Learning.ipynb) | Bridging classical image processing with modern deep learning paradigms | 🟡 Intermediate |
| [**Convolutional Neural Networks (CNN)**](https://github.com/nielitropar/computer-vision/blob/main/Convolutional_Neural_Networks_(CNN).ipynb) | Deep dive into CNN layers — convolution, pooling, activation, and fully connected layers | 🟡 Intermediate |
| [**Inside the CNN (Not a Black Box)**](https://github.com/nielitropar/computer-vision/blob/main/Inside_the_CNN_(Not_a_Black_Box).ipynb) | Visualizing feature maps, filters, and gradient-weighted class activation maps (Grad-CAM) | 🔴 Advanced |

**Key concepts covered:** Image representation, convolutions, pooling, activation functions, feature map visualization, Grad-CAM, receptive fields.

---

### 2️⃣ Object Detection & YOLO

> **Goal:** Detect and localize multiple objects in real-time across images and video streams.

A comprehensive, end-to-end module on object detection using the **YOLO (You Only Look Once)** family of models — from annotation to training to inference.

| Notebook | Description | Level |
|---|---|---|
| [**Beginner Object Detection with YOLOv8 & LabelImg**](https://github.com/nielitropar/computer-vision/blob/main/Beginner_Object_Detection_with_YOLOv8_and_LabelImg.ipynb) | Introduction to YOLOv8 architecture and hands-on bounding box annotation with LabelImg | 🟢 Beginner |
| [**Train YOLOv8 on Custom Dataset**](https://github.com/nielitropar/computer-vision/blob/main/train_yolov8_object_detection_on_custom_dataset.ipynb) | Full end-to-end pipeline: dataset prep → training → evaluation → inference | 🟡 Intermediate |
| [**YOLO Complete — Images & Video**](https://github.com/nielitropar/computer-vision/blob/main/yolo_complete_image_video.ipynb) | Applying YOLOv8 inference to static images and live video streams | 🟡 Intermediate |
| [**Pascal VOC (XML) → YOLO Format**](https://github.com/nielitropar/computer-vision/blob/main/Pascal_VOC_(XML)_to_YOLO_format.ipynb) | Utility notebook for converting Pascal VOC XML annotations to YOLO `.txt` format | 🟢 Beginner |

**Key concepts covered:** YOLO architecture, bounding box regression, IoU, NMS, anchor boxes, dataset annotation, custom training, mAP evaluation.

---

### 3️⃣ Image Classification (MNIST, Fashion, Animals)

> **Goal:** Build progressively sophisticated classifiers, from MLPs on handwritten digits to CNNs on animal images.

This module follows the traditional "Hello World" path of deep learning, starting with MNIST and expanding to real-world datasets.

| Notebook | Description | Level |
|---|---|---|
| [**Hello World of Deep Learning (MNIST Beginners)**](https://github.com/nielitropar/computer-vision/blob/main/mnist_for_beginners.ipynb) | Your first neural network — the classic entry point for any deep learning practitioner | 🟢 Beginner |
| [**MNIST Data Exploration**](https://github.com/nielitropar/computer-vision/blob/main/mnist_data_exploration.ipynb) | Thorough EDA of the MNIST dataset: distributions, sample visualizations, and class balance | 🟢 Beginner |
| [**MNIST MLP Complete**](https://github.com/nielitropar/computer-vision/blob/main/mnist_mlp_complete.ipynb) | Full Multilayer Perceptron implementation with training, evaluation, and confusion matrix | 🟡 Intermediate |
| [**Fashion MNIST with TensorFlow**](https://github.com/nielitropar/computer-vision/blob/main/Fashion_MNIST_Tensorflow.ipynb) | Expanding classification to 10 clothing categories using CNN + TensorFlow/Keras | 🟡 Intermediate |
| [**Dogs vs. Cats**](https://github.com/nielitropar/computer-vision/blob/main/Dogs_vs_Cats.ipynb) | Binary image classification on real-world data with data augmentation and callbacks | 🟡 Intermediate |

**Key concepts covered:** MLPs, softmax, cross-entropy loss, data augmentation, dropout, batch normalization, model evaluation.

---

### 4️⃣ Facial Recognition

> **Goal:** Understand and implement the complete facial recognition pipeline — from raw image to identity verification.

A dedicated, three-part module that walks through the entire face recognition stack with growing complexity.

| Notebook | Description | Level |
|---|---|---|
| [**Facial Recognition Theory (Presentation)**](https://docs.google.com/presentation/d/1LTxo4PH-qyxwEUVq58861jwmCPExnXcAHOkyP4pJDNM/edit?usp=sharing) | Slide deck covering theoretical foundations: face detection pipelines, embeddings, and matching | 🟢 Beginner |
| [**Face Recognition Module 1**](https://github.com/nielitropar/computer-vision/blob/main/Face_Recognition_Modue_1.ipynb) | Fundamentals of face detection using Haar Cascades and DNN-based detectors | 🟢 Beginner |
| [**Face Recognition Module 2**](https://github.com/nielitropar/computer-vision/blob/main/Face_Recognition_Modue_2.ipynb) | Feature extraction, 68-point facial landmark detection, and face embeddings with FaceNet | 🟡 Intermediate |
| [**Face Recognition Module 3**](https://github.com/nielitropar/computer-vision/blob/main/Face_Recognition_Modue_3.ipynb) | Advanced recognition: embedding comparison, database matching, and deployment pipelines | 🔴 Advanced |

**Key concepts covered:** Haar Cascades, MTCNN, face alignment, 68-point landmarks, FaceNet, triplet loss, cosine similarity, embedding databases.

---

### 5️⃣ Image Segmentation

> **Goal:** Go beyond bounding boxes to achieve precise, pixel-level understanding of images.

| Notebook | Description | Level |
|---|---|---|
| [**U-Net Segmentation Practical**](https://github.com/nielitropar/computer-vision/blob/main/unet_segmentation_practical.ipynb) | Full implementation of the U-Net encoder-decoder architecture for semantic segmentation with custom datasets | 🔴 Advanced |

**Key concepts covered:** Semantic vs. instance segmentation, encoder-decoder architecture, skip connections, U-Net, Dice loss, IoU metrics, mask prediction.

---

### 6️⃣ Transfer Learning & Edge Deployment

> **Goal:** Leverage powerful pre-trained models and deploy them to resource-constrained environments.

| Notebook | Description | Level |
|---|---|---|
| [**3-Class Classifier — MobileNetV2 + TFLite**](https://github.com/nielitropar/computer-vision/blob/main/3_Class_Classifier_MobileNetV2_Transfer_Learning_%C2%B7_TFLite.ipynb) | Fine-tune MobileNetV2 with Transfer Learning on a custom 3-class dataset, then export to TensorFlow Lite for mobile/edge inference | 🟡 Intermediate |

**Key concepts covered:** Transfer learning, feature extraction vs. fine-tuning, MobileNetV2, depthwise separable convolutions, TFLite conversion, quantization, on-device inference.

---

## 🗺️ Learning Path

Not sure where to start? Follow the recommended path below based on your background:

**🔰 Absolute Beginner**
```
MNIST Beginners → MNIST Data Exploration → MNIST MLP Complete → Intro to Computer Vision → CNNs
```

**📈 Some ML Background**
```
CNNs → Inside the CNN → Dogs vs. Cats → Fashion MNIST → YOLOv8 Beginner → Transfer Learning
```

**🚀 Practitioner / Researcher**
```
Train YOLOv8 Custom → U-Net Segmentation → Face Recognition Series → TFLite Deployment
```

---

## 🚀 Getting Started

### Prerequisites

| Option | Details |
|---|---|
| ☁️ **Google Colab (Recommended)** | Zero setup required. All notebooks include a "Open in Colab" compatible structure. GPU acceleration available for free. |
| 💻 **Local Setup** | Python 3.8+, Jupyter Notebook or JupyterLab. A virtual environment is strongly recommended. NVIDIA GPU optional but beneficial for training. |

### Installation

**Step 1 — Clone the repository**
```bash
git clone https://github.com/nielitropar/computer-vision.git
cd computer-vision
```

**Step 2 — Create and activate a virtual environment** *(recommended)*
```bash
# Using conda
conda create -n cv-dl python=3.10
conda activate cv-dl

# OR using venv
python -m venv cv-dl
source cv-dl/bin/activate        # Linux/macOS
cv-dl\Scripts\activate           # Windows
```

**Step 3 — Install all dependencies**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn \
            opencv-python pillow \
            tensorflow torch torchvision \
            ultralytics \
            jupyter jupyterlab
```

**Step 4 — Launch Jupyter**
```bash
jupyter notebook
# OR
jupyter lab
```

Then navigate to any notebook and start learning! 🎉

### GPU Support

For significantly faster training, CUDA-enabled GPU usage is recommended:

```bash
# TensorFlow with GPU support
pip install tensorflow[and-cuda]

# PyTorch with CUDA (adjust for your CUDA version)
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
```

---

## 📦 Dependencies Summary

| Library | Purpose | Version |
|---|---|---|
| `numpy` | Numerical computing | ≥ 1.23 |
| `pandas` | Data manipulation | ≥ 1.5 |
| `matplotlib` / `seaborn` | Visualization | ≥ 3.6 |
| `opencv-python` | Image processing | ≥ 4.7 |
| `tensorflow` | Deep learning (Keras API) | ≥ 2.12 |
| `torch` / `torchvision` | Deep learning (PyTorch) | ≥ 2.0 |
| `ultralytics` | YOLOv8 object detection | ≥ 8.0 |
| `scikit-learn` | ML utilities & metrics | ≥ 1.2 |
| `pillow` | Image I/O | ≥ 9.0 |
| `jupyter` | Notebook environment | ≥ 1.0 |

---

## 📁 Repository Structure

```
computer-vision/
│
├── 📂 Core CV & CNNs
│   ├── Intro_to_Computer_Vision.ipynb
│   ├── Computer_Vision_with_Deep_Learning.ipynb
│   ├── Convolutional_Neural_Networks_(CNN).ipynb
│   └── Inside_the_CNN_(Not_a_Black_Box).ipynb
│
├── 📂 Object Detection
│   ├── Beginner_Object_Detection_with_YOLOv8_and_LabelImg.ipynb
│   ├── train_yolov8_object_detection_on_custom_dataset.ipynb
│   ├── yolo_complete_image_video.ipynb
│   └── Pascal_VOC_(XML)_to_YOLO_format.ipynb
│
├── 📂 Image Classification
│   ├── mnist_for_beginners.ipynb
│   ├── mnist_data_exploration.ipynb
│   ├── mnist_mlp_complete.ipynb
│   ├── Fashion_MNIST_Tensorflow.ipynb
│   └── Dogs_vs_Cats.ipynb
│
├── 📂 Facial Recognition
│   ├── Face_Recognition_Modue_1.ipynb
│   ├── Face_Recognition_Modue_2.ipynb
│   └── Face_Recognition_Modue_3.ipynb
│
├── 📂 Segmentation
│   └── unet_segmentation_practical.ipynb
│
├── 📂 Transfer Learning & Edge AI
│   └── 3_Class_Classifier_MobileNetV2_Transfer_Learning_·_TFLite.ipynb
│
└── README.md
```

---

## 🤝 Acknowledgments

<div align="center">

<img src="https://raw.githubusercontent.com/nielitropar/computer-vision/refs/heads/main/assets/Sarwan_Singh.JPG" width="150" alt="Dr. Sarwan Singh"/>

**Dr. Sarwan Singh**, Scientist-D  
*Joint Director, NIELIT Deemed to be University, Main Campus Ropar*

</div>

<br/>

This repository was prepared and authored by **Dr. Sarwan Singh, Scientist-D**, and developed under the academic framework of **NIELIT Deemed to be University, Main Campus Ropar**.

If you find this resource helpful in your research or teaching, consider starring ⭐ the repository to help others discover it.

---

## 📄 License

This repository is intended for **academic and educational use**. Please credit the author and institution when referencing or adapting any material from this repository.

---

<div align="center">

Made with ❤️ for the Computer Vision & AI community  
**NIELIT Deemed to be University, Main Campus Ropar**

</div>
