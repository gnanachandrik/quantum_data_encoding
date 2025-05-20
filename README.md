# Quantum_Data_Encoding
# Advanced Algorithm-Based Quantum Data Encoding with Quantum Algorithms
This project explores a hybrid machine learning approach that combines classical techniques with quantum computing to classify images from an Advanced Driver Assistance System (ADAS) dataset.

I) Overview:
The goal is to leverage the strengths of both classical and quantum computing to improve image classification performance. The pipeline integrates Principal Component Analysis (PCA) for dimensionality reduction and Quantum Kernel Estimation (QKE) for enhanced feature mapping, followed by a Support Vector Machine (SVM) for final classification.

II) Methodology:
- PCA is applied to reduce the high-dimensional image data into a compact set of features.
- The reduced features are encoded into quantum states using amplitude encoding.
- A quantum kernel matrix is computed using PennyLane to measure the similarity between quantum-encoded samples.
- A classical SVM is then trained on the quantum kernel matrix for classification.
- The classical processing is handled using Scikit-learn.

III) Tools and Libraries:
- PennyLane – Quantum computing framework
- Scikit-learn – Machine learning tools for PCA and SVM
- Python 3.11.1 (VSCODE)
- Dataset Description: https://datasetninja.com/adas#introduction
- Dataset Download: https://www.kaggle.com/datasets/prabhusomsaitalari/dataset-for-driver-assistant-ml-models

IV) Dataset:
The dataset consists of ADAS-related images collected from multiple mobile devices, including:
- iphone 12
- VIVO Y51A
Each image is labeled according to ADAS features such as potholes, road markings, speed breakers, etc.

V) Result:
The model achieves an overall accuracy of 65%, with relatively balanced performance across both devices.

VI) Acknowledgments:
This project was made possible with the help of open-source tools and the quantum computing community. 
