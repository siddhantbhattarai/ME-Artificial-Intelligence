# **Comprehensive Guide to Deep Learning (DL)**

This repository contains a **detailed guide on Deep Learning (DL)** with Python implementations for **image classification using Convolutional Neural Networks (CNNs)** and explanations of key concepts such as **backpropagation, optimization, and activation functions**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Deep Learning (DL)**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-deep-learning-dl)

---

## **📁 Project Structure**

- `Deep_Learning_CNN_MNIST.ipynb`: Contains the Python implementation of a CNN for digit classification using the **MNIST dataset**.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **Deep Learning Overview**:
   - Neural networks, key components (input, hidden, output layers).
   - Forward propagation, backpropagation, and loss functions.
2. **Python Implementation**:
   - Example of a **Convolutional Neural Network (CNN)** for image classification.
   - Explanation of **ReLU, Softmax** activation functions and **Adam Optimizer**.
3. **Performance Metrics**:
   - Training accuracy, validation accuracy, and loss plots.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `tensorflow`, `numpy`, `matplotlib`

Install dependencies using:
```bash
pip install tensorflow numpy matplotlib notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Deep_Learning_CNN_MNIST.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

- **Accuracy:** Proportion of correct predictions.
- **Validation Loss:** Measures the difference between predicted and actual values during validation.
- **Convergence Time:** Number of epochs required for the model to converge.
- **Loss Curve:** Visualizes the training and validation loss to identify overfitting or underfitting.

---

## **📝 Example Overview**

- **Dataset:** MNIST (handwritten digits 0-9).
- **Model Architecture:**
  - **Input Layer:** 28x28 grayscale images.
  - **Convolutional Layer:** 32 filters, ReLU activation.
  - **Pooling Layer:** 2x2 max pooling.
  - **Fully Connected Layers:** Dense layers for classification.
  - **Output Layer:** 10 neurons (one for each digit).
- **Hyperparameters:**
  - **Epochs:** 5.
  - **Batch Size:** 32.
  - **Learning Rate:** Controlled by the **Adam Optimizer**.

### **Sample Output:**
```bash
Test Accuracy: 0.9841
```
The CNN achieves a high accuracy for handwritten digit classification.

---

## **💡 Troubleshooting Common Errors**

1. **Memory Allocation Warnings:**
   - If you encounter memory-related warnings, try reducing the batch size:
     ```python
     model.fit(X_train, y_train, epochs=5, batch_size=16)
     ```

2. **cuDNN or cuBLAS Registration Errors:**
   - Run the model using CPU if GPU-related issues occur:
     ```bash
     export CUDA_VISIBLE_DEVICES=""
     ```

3. **Warning: Input Shape:**
   - Instead of passing `input_shape` to the first layer, use an explicit `Input` layer:
     ```python
     from tensorflow.keras.layers import Input
     Input(shape=(28, 28, 1))
     ```

---

## **💡 Feedback and Contact**

If you found this project helpful or have any suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-deep-learning-dl).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
