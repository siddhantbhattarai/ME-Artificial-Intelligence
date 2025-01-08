# **Comprehensive Guide to Probabilistic Reasoning and Bayesian Networks**

This repository contains a **detailed guide on Probabilistic Reasoning and Bayesian Networks** with Python implementations for **probability-based inference and decision-making** using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Probabilistic Reasoning and Bayesian Networks**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-probabilistic-reasoning-and-bayesian-networks)

---

## **📁 Project Structure**

- `Bayesian_Network.ipynb`: Contains the complete Python implementation, explanations, and visualizations for building a Bayesian Network and performing probabilistic inference.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **Bayesian Network Overview**:
   - Representation of variables and dependencies using Directed Acyclic Graph (DAG).
   - Joint Probability Distribution (JPD) from conditional probability tables (CPTs).
2. **Python Implementation**:
   - Example Bayesian Network for medical diagnosis using `pgmpy`.
   - Definition of nodes, edges, and conditional probability tables (CPTs).
   - Performing probabilistic inference using **Variable Elimination**.
3. **Performance Evaluation**:
   - Accuracy of predictions, log-likelihood scores, and inference time.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `numpy`, `pandas`, `pgmpy`, `matplotlib`

Install dependencies using:
```bash
pip install numpy pandas pgmpy matplotlib notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Bayesian_Network.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

- **Log-Likelihood Score:** Measures how well the network explains the observed data.
- **Accuracy:** Proportion of correct predictions for classification tasks.
- **Inference Time:** Time taken to compute posterior probabilities given evidence.
- **Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC):** Metrics to evaluate the goodness of fit while penalizing model complexity.

---

## **📝 Example Overview**

- **Bayesian Network Structure:** A simple DAG with variables "Flu," "Fever," "Cough," and "BodyAche."
- **Conditional Probability Tables (CPTs):**
  - Example: Probability of "Fever" given "Flu."
- **Inference Task:** Compute the probability of "Flu" given evidence that "BodyAche" is present.

### **Sample Query:**
For evidence:
```bash
BodyAche = True
```
The output might be:
```bash
+--------+--------------+
| Flu    | Probability  |
+--------+--------------+
| Flu(0) | 0.70         |
| Flu(1) | 0.30         |
+--------+--------------+
```

---

## **💡 Feedback and Contact**

If you found this project helpful or have suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-probabilistic-reasoning-and-bayesian-networks).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
