# **Comprehensive Guide to Support Vector Machine (SVM)**

This repository contains a **detailed guide on Support Vector Machines (SVM)** with Python implementations for **classification** and **regression** tasks using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Support Vector Machine (SVM)**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-support-vector-machine-svm)

---

## **📁 Project Structure**

- `Support_Vector_Machine.ipynb`: Contains the complete Python implementation, explanations, and visualizations for both SVM classification and regression.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **SVM Algorithm Overview**:
   - Linear SVM and Soft Margin SVM.
   - Non-Linear SVM with Kernel Trick (RBF, Polynomial, Linear).
   - Hyperparameter tuning (`C`, `gamma`, `epsilon`) for SVM and SVR.
2. **Python Implementations**:
   - **Classification Example:** Classifying the Iris flower species using SVM.
   - **Regression Example:** Predicting California house prices using SVR (Support Vector Regression).
3. **Performance Evaluation**:
   - Accuracy, classification report, MAE, MSE, and R² score.

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
3. Open `Support_Vector_Machine.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

### **Classification Metrics:**
- **Accuracy:** Proportion of correctly classified instances.
- **Precision:** Proportion of true positives out of all predicted positives.
- **Recall:** Proportion of true positives out of all actual positives.
- **F1-Score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Summary of true positives, true negatives, false positives, and false negatives.

### **Regression Metrics (for SVR):**
- **Mean Absolute Error (MAE):** Average magnitude of errors between predictions and actual values.
- **Mean Squared Error (MSE):** Penalizes larger errors by squaring them.
- **R² Score:** Proportion of variance explained by the model.

---

## **📝 Example Overview**

- **Classification Example:** Classifying Iris flower species based on sepal and petal dimensions.
  - **Dataset:** Iris dataset (3 flower species, 4 features).
  - **Kernel Used:** RBF (Radial Basis Function) kernel.
  - **Evaluation:** Accuracy and classification report.

- **Regression Example:** Predicting house prices using SVR.
  - **Dataset:** California Housing dataset.
  - **Kernel Used:** RBF kernel.
  - **Evaluation:** MAE, MSE, and R² score.

---

## **💡 Feedback and Contact**

If you found this project helpful or have suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-support-vector-machine-svm).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
