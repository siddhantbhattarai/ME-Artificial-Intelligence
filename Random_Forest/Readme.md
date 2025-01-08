# **Comprehensive Guide to Random Forest**

This repository contains a **detailed guide on the Random Forest algorithm** with Python implementations for **classification** and **regression** tasks using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Random Forest**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-random-forest)

---

## **📁 Project Structure**

- `Random_Forest_Algorithm.ipynb`: Contains the complete Python implementation, explanations, and visualizations for Random Forest classification and regression.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **Random Forest Algorithm Overview**:
   - Bootstrap sampling and random feature selection (feature bagging).
   - Aggregation of predictions using majority voting (classification) or averaging (regression).
2. **Python Implementations**:
   - **Classification Example:** Using the Iris dataset to classify flower species.
   - **Regression Example:** Using the California Housing dataset to predict house prices.
3. **Performance Evaluation**:
   - Accuracy, classification report, mean absolute error (MAE), mean squared error (MSE), and R² score.

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
3. Open `Random_Forest_Algorithm.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

### **Classification Metrics:**
- **Accuracy:** Proportion of correctly predicted instances.
- **Precision:** Proportion of true positives out of all positive predictions.
- **Recall:** Proportion of true positives out of all actual positives.
- **F1-Score:** Harmonic mean of precision and recall.

### **Regression Metrics:**
- **Mean Absolute Error (MAE):** Average magnitude of errors between predictions and actual values.
- **Mean Squared Error (MSE):** Average of squared differences between predictions and actual values.
- **R-Squared (R²):** Proportion of variance explained by the model.

---

## **📝 Example Overview**

- **Classification Example:** Classifying Iris flower species based on sepal and petal dimensions.
  - **Dataset:** Iris dataset (3 flower species, 4 features).
  - **Number of Trees:** 100.
  - **Max Depth:** 4.
  - **Evaluation:** Accuracy and classification report.
  
- **Regression Example:** Predicting house prices based on features like location and room count.
  - **Dataset:** California Housing dataset (predicting median house value).
  - **Number of Trees:** 100.
  - **Max Depth:** 10.
  - **Evaluation:** MAE, MSE, and R² score.

---

## **💡 Feedback and Contact**

If you found this project helpful or have suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-random-forest).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.
