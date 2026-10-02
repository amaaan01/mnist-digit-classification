```markdown
# MNIST Handwritten Digit Classification

A Deep Learning project that builds and evaluates a Feedforward Neural Network using **TensorFlow** and **Keras** to classify handwritten digits (0–9) from the classic **MNIST dataset**.

```

---

## 📌 Project Overview

This project demonstrates an end-to-end Machine Learning pipeline in Python:

* Loading and preprocessing the MNIST dataset.
* Normalizing pixel values for optimal model convergence.
* Building a multi-layer Neural Network with ReLU activation functions and Softmax output.
* Training and evaluating the model on test data, achieving **~97.57% accuracy**.
* Visualizing predictions and confusion metrics using Matplotlib.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Deep Learning Framework:** TensorFlow / Keras
* **Data Manipulation & Math:** NumPy
* **Data Visualization:** Matplotlib
* **Model Evaluation:** Scikit-Learn

---

## 🧠 Model Architecture

| Layer | Type | Output Shape | Activation |
| --- | --- | --- | --- |
| Input | Flatten | (784,) | None |
| Hidden Layer 1 | Dense | (128,) | ReLU |
| Hidden Layer 2 | Dense | (32,) | ReLU |
| Output Layer | Dense | (10,) | Softmax |

* **Loss Function:** Sparse Categorical Crossentropy
* **Optimizer:** Adam

---

## 📊 Results

* **Test Accuracy:** ~97.57%
* **Performance:** Successfully classifies handwritten digits with high confidence across all 10 digit categories.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/amaaan01/mnist-digit-classification.git](https://github.com/amaaan01/mnist-digit-classification.git)
cd mnist-digit-classification

```

### 2. Install Dependencies

```bash
pip install tensorflow matplotlib numpy scikit-learn jupyter

```

### 3. Run the Notebook

```bash
jupyter notebook mnist_neural_network.ipynb

```

---

## 📂 Repository Structure

```text
mnist-digit-classification/
├── .gitignore                   # Git ignore file
├── mnist_neural_network.ipynb   # Main Jupyter Notebook with training & analysis
└── README.md                    # Project documentation

```

```

```
