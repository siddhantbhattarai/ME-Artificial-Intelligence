# **Comprehensive Guide to Self-Organizing Map (SOM)**

This repository contains a **detailed guide on Self-Organizing Maps (SOM)** with Python implementations for **clustering and data visualization** tasks using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Self-Organizing Map (SOM)**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-self-organizing-map-som)

---

## **📁 Project Structure**

- `Self_Organizing_Map.ipynb`: Contains the complete Python implementation, explanations, and visualizations for clustering using SOM.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **SOM Algorithm Overview**:
   - Best Matching Unit (BMU) identification using Euclidean distance.
   - Weight updates based on learning rate and neighborhood function.
   - Visualization of the 2D SOM grid.
2. **Python Implementation**:
   - Example of clustering synthetic data points using SOM.
   - Visualization of clusters on the SOM grid.
3. **Performance Evaluation**:
   - Quantization error and topographic error for SOM.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `numpy`, `matplotlib`, `minisom`, `scikit-learn`

Install dependencies using:
```bash
pip install numpy matplotlib minisom scikit-learn notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Self_Organizing_Map.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

- **Quantization Error (QE):** Average distance between input vectors and their Best Matching Units (BMUs).
- **Topographic Error:** Proportion of input vectors for which the first and second BMUs are not adjacent.
- **Silhouette Score:** Measures how well data points fit within their assigned clusters.
- **Cluster Visualization:** 2D grid showing data points and their corresponding BMUs.

---

## **📝 Example Overview**

- **Dataset:** Synthetic dataset with clustered data points.
- **Grid Size:** 10x10 SOM grid (100 neurons).
- **Training Iterations:** 1000 iterations.
- **Learning Rate and Neighborhood Function:** Gaussian decay to ensure convergence.

---

## **💡 Feedback and Contact**

If you found this project helpful or have suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-self-organizing-map-som).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
