# 🧠 Geometric Shape Classifier

A MATLAB project focused on image classification using **Feedforward Artificial Neural Networks (ANNs)**.

Developed as the practical assignment for the **Knowledge and Reasoning** course of the **BSc in Computer Science** at **ISEC – Coimbra Institute of Engineering (2021/2022)**.

---

## 📖 About

The objective of this project was to study and compare different neural network architectures capable of classifying six geometric shapes from binary images.

The project includes:

- Image preprocessing
- Neural network training
- Hyperparameter experimentation
- Model evaluation
- Classification of unseen images
- Classification of custom hand-drawn shapes

---

## 🎯 Geometric Shapes

The neural network learns to classify the following classes:

- Circle
- Kite
- Parallelogram
- Square
- Trapezoid
- Triangle

---

## 🖼️ Image Processing

Before training, every image goes through a preprocessing pipeline:

- Resize images from **224×224** to **25×25**
- Convert to binary images
- Flatten images into column vectors
- Generate target matrices for supervised learning

This significantly reduces training time while maintaining good classification performance.

---

## 🧠 Neural Network Experiments

Several neural network configurations were tested, including:

- Different numbers of hidden layers
- Different neuron counts
- Multiple activation functions
- Multiple training algorithms
- Different dataset partition strategies
- Different data division methods

Each configuration was evaluated using accuracy and confusion matrices.

---

## 📊 Results

Some of the main conclusions obtained during the experiments were:

- Multi-layer networks generally performed better than single-layer networks.
- **trainlm** produced the best overall results.
- A **90% / 5% / 5%** dataset split achieved the highest performance.
- The best model reached approximately **96% classification accuracy** after training with all available datasets.

---

## 📂 Dataset

The provided dataset is divided into three folders:

| Folder | Description |
|---------|-------------|
| **start** | Initial dataset (5 images per class) |
| **train** | Training dataset (50 images per class) |
| **test** | Unseen dataset (10 images per class) |

Additionally, custom images were created to evaluate the model's ability to generalize to unseen drawings.

---

## 🛠️ Built With

- MATLAB
- Neural Network Toolbox
- Image Processing Toolbox

---

## 📁 Project Structure

```text
ArtificialNeuralNetworks/
│
├── Code/
├── Images/
├── Networks/
├── Report/
└── README.md
```

---

## 📸 Preview
![Application](https://user-images.githubusercontent.com/82268859/175390906-ffeca577-a4af-41a8-bfb1-166357166425.png)

---

## 📄 License


This project was developed for the **Knowledge and Reasoning** course at the **Instituto Superior de Engenharia de Coimbra (ISEC)**.

It is intended for educational purposes.
