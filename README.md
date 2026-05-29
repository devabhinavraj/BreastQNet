# GAE-QCNet: Explainable Hybrid Quantum–Classical Breast Cancer Classification System

## Overview

GAE-QCNet is a hybrid Quantum–Classical Deep Learning framework designed for breast cancer classification using histopathological images. The model combines a Convolutional Neural Network (CNN) for classical feature extraction with a Quantum Convolutional Neural Network (QCNN) for quantum feature transformation.

A Genetic Algorithm (GA) is employed to automatically optimize the quantum circuit architecture by discovering effective gate configurations and entanglement patterns. The proposed framework aims to improve feature representation, classification performance, and interpretability within a hybrid quantum–classical setting.

---

## Key Features

* Hybrid CNN–QCNN architecture
* Quantum feature encoding using rotation gates
* Parameterized quantum convolution layer
* Genetic Algorithm-based quantum circuit search
* Adaptive entanglement optimization
* End-to-end hybrid training
* Explainable quantum feature analysis
* Breast cancer classification using histopathological images

---

## Architecture

Input Histopathological Image

↓

CNN Feature Extraction

↓

Feature Vector Reduction

↓

Quantum Feature Encoding (Ry, Rx, Rz)

↓

Quantum Convolution Layer

↓

Entanglement Operations (CNOT)

↓

Genetic Algorithm Circuit Optimization

↓

Expectation Value Measurement

↓

Fully Connected Layer

↓

Sigmoid Classification Output

---

## Dataset

The model is evaluated on the **BreaKHis** histopathological breast cancer dataset.

Classes:

* Benign
* Malignant

Magnification Levels:

* 40×
* 100×
* 200×
* 400×

---

## Technologies Used

* Python
* TensorFlow / Keras
* PennyLane
* NumPy
* Matplotlib
* Scikit-learn
* Genetic Algorithm

---

## Quantum Components

### Quantum Encoding

Classical CNN features are encoded into quantum states using rotation gates:

* Ry
* Rx
* Rz

### Quantum Convolution Layer

The QCNN layer consists of:

* Parameterized rotation gates
* Learnable quantum parameters
* Entanglement operations

### Measurement

Quantum information is extracted using Pauli-Z expectation values and converted into a classical feature vector for final classification.

---

## Genetic Algorithm Optimization

The Genetic Algorithm searches for an optimized quantum circuit by evolving:

* Quantum gate configurations
* Circuit depth
* Entanglement patterns
* Local and global qubit connectivity

The best-performing circuit is selected and integrated into the final hybrid architecture.

---

## Performance

| Model                          | Accuracy |
| ------------------------------ | -------- |
| Classical CNN Baseline         | Baseline |
| Simple QCNN (Fixed Circuit)    | 85.47%   |
| QCNN without Genetic Algorithm | 90.80%   |
| Proposed GAE-QCNet             | 92.13%   |

---

## Research Contribution

* Hybrid Quantum–Classical Breast Cancer Classification
* Genetic Algorithm-Based Quantum Circuit Search
* Adaptive Entanglement Optimization
* Explainable Quantum Feature Representation
* End-to-End Hybrid Learning Framework

---

## Citation

If you use this work in your research, please cite the associated paper:

**GAE-QCNet: Explainable Hybrid Quantum–Classical Breast Cancer Classification System Using Genetic Algorithm-Based Quantum Circuit Optimization**
