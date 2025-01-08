# **Comprehensive Guide to Boltzmann Machine (BM)**

This repository contains a **detailed guide on Boltzmann Machines (BM)** with a Python implementation for **feature learning and reconstruction** using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Boltzmann Machine (BM)**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-boltzmann-machine-bm)

---

## **📁 Project Structure**

- `Boltzmann_Machine.ipynb`: Contains the complete Python implementation, explanations, and visualizations for training and testing a Restricted Boltzmann Machine (RBM).

---

## **🚀 What's Included**

The notebook demonstrates:
1. **Boltzmann Machine Overview**:
   - Energy-based neural network for unsupervised learning.
   - Structure and energy function of Boltzmann Machines.
   - Explanation of Restricted Boltzmann Machines (RBMs) for dimensionality reduction and feature extraction.
2. **Python Implementation**:
   - Example of using **RBM** for feature learning with the **digits dataset**.
   - Training the model and reconstructing data.
3. **Performance Evaluation**:
   - Reconstruction error and convergence time.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

Install dependencies using:
```bash
pip install numpy pandas scikit-learn matplotlib notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Boltzmann_Machine.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

- **Reconstruction Error:** Measures the difference between the input data and the reconstructed data.
- **Log-Likelihood:** Measures how well the RBM models the distribution of the input data.
- **Training Time:** Time taken to train the model.
- **Convergence Time:** Number of epochs required for the model to reach a stable state.
- **Accuracy (for Classification Tasks):** Percentage of correct predictions (if the RBM is fine-tuned for classification).

---

## **📝 Example Overview**

- **Dataset:** Digits dataset (binary pixel images of handwritten digits).
- **RBM Parameters:**
  - **Hidden Units:** 64 (to learn compact feature representations).
  - **Learning Rate:** 0.1.
  - **Iterations:** 10 epochs.
- **Training and Reconstruction:**
  - After training, the model reconstructs the input data to evaluate its feature-learning capability.

### **Sample Output:**
```bash
Reconstructed data shape: (1797, 64)
```
The RBM learns features and reconstructs a compressed version of the input data.

---

## **💡 Feedback and Contact**

If you found this project helpful or have any suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-boltzmann-machine-bm).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
