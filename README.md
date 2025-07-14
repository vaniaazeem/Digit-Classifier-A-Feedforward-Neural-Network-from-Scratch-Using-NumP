# 🧠 Simple Neural Network from Scratch

This project implements a **basic feedforward neural network** from scratch using **Python** and **NumPy**. It is trained on the **MNIST dataset** to classify handwritten digits (0-9), demonstrating core concepts of neural networks without relying on high-level libraries like TensorFlow or PyTorch.

---

## 🚀 Features

- Implements a multi-layer feedforward neural network
- Uses sigmoid activation functions
- Supports backpropagation and gradient descent
- Trains and evaluates on the MNIST dataset
- Fully written in NumPy (no deep learning libraries used)

---

## 🗂️ Project Structure

- `Neural Network.ipynb` - Main Jupyter notebook implementing and training the neural network
- `data/` (optional) - Directory to store the MNIST dataset if needed locally

---

## 📊 Dataset

This project uses the **MNIST dataset**, which consists of 70,000 labeled images of handwritten digits (28x28 pixels).

- Training set: 60,000 images
- Test set: 10,000 images

If the notebook includes code to download it via `keras.datasets.mnist`, no manual download is necessary.

---

## ⚙️ Requirements

- Python 3.x
- NumPy
- Matplotlib (for visualizations, optional)
- Jupyter Notebook

You can install the requirements using pip:

```bash
pip install numpy matplotlib notebook
