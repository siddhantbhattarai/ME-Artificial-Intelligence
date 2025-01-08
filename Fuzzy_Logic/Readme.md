# **Comprehensive Guide to Fuzzy Logic**

This repository contains a **detailed guide on Fuzzy Logic** with a Python implementation for a **fuzzy control system** using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Fuzzy Logic**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-fuzzy-logic)

---

## **📁 Project Structure**

- `Fuzzy_Logic_System.ipynb`: Contains the complete Python implementation, explanations, and visualizations for a fuzzy logic-based fan control system.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **Fuzzy Logic System Overview**:
   - Fuzzification: Converting crisp inputs into fuzzy values.
   - Inference Engine: Applying "IF-THEN" rules to generate fuzzy outputs.
   - Defuzzification: Converting fuzzy outputs into crisp values.
2. **Python Implementation**:
   - Example of a **fan speed control system** based on **temperature** and **humidity**.
   - Visualization of membership functions and fuzzy control rules.
3. **Performance Metrics**:
   - Quantization error, system interpretability, and robustness.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `numpy`, `matplotlib`, `scikit-fuzzy`

Install dependencies using:
```bash
pip install numpy matplotlib scikit-fuzzy notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Fuzzy_Logic_System.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

- **Accuracy:** How close the system's outputs are to the expected outputs.
- **Interpretability:** The ease with which the membership functions and rules can be understood.
- **Robustness:** The system's ability to handle noisy or incomplete data.
- **Response Time:** Time taken by the system to produce an output after receiving an input.

---

## **📝 Example Overview**

- **Input Variables:** Temperature (0°C to 40°C) and Humidity (0% to 100%).
- **Output Variable:** Fan Speed (0% to 100%).
- **Membership Functions:** Triangular functions for "cold," "warm," and "hot" temperature, and "low," "medium," "high" humidity.
- **Rules:**
  - **Rule 1:** IF temperature is cold AND humidity is low, THEN fan speed is low.
  - **Rule 2:** IF temperature is warm AND humidity is medium, THEN fan speed is medium.
  - **Rule 3:** IF temperature is hot AND humidity is high, THEN fan speed is high.

### **Sample Output:**
For an input of **35°C temperature** and **70% humidity**, the system may output:
```bash
Fan Speed: 80.3%
```

---

## **💡 Feedback and Contact**

If you found this project helpful or have any suggestions, feel free to:
- Leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-fuzzy-logic).
- Open an issue in this repository.

---

## **📝 License**

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.

---
