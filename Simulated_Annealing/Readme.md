# **Comprehensive Guide to Simulated Annealing: Concepts, Applications, and Code Example**

This repository contains a **detailed guide on Simulated Annealing** along with a Python implementation of the algorithm for **function minimization** using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For detailed explanations, read the full blog post:  
[**Comprehensive Guide to Simulated Annealing**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-simulated-annealing)

---

## **📁 Project Structure**

- `Simulated_Annealing.ipynb`: Contains the Python code for simulated annealing, explanations, and visualizations.

---

## **🚀 What's Included**

The notebook demonstrates the following:
1. **Simulated Annealing Algorithm Steps**:
   - Initialization with an initial solution and temperature.
   - Neighbor generation and acceptance criteria.
   - Cooling schedule and stopping criteria.
2. **Implementation**: Python example for minimizing the function \( f(x) = (x - 3)^2 + 4 \).
3. **Visualization**: Plot showing cost convergence over iterations.

---

## **🔧 Prerequisites**

Ensure you have the following installed:
- **Python (>= 3.7)**
- **Jupyter Notebook**
- Libraries: `numpy`, `matplotlib`

Install dependencies using:
```bash
pip install numpy matplotlib notebook
```

---

## **▶️ Running the Notebook**

1. Open the terminal and navigate to the folder containing the notebook.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Open `Simulated_Annealing.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

The notebook evaluates the following:
- **Best Solution:** The solution that minimizes the cost function.
- **Best Cost:** The minimum value of the objective function.
- **Cost Convergence:** Visualized using a plot of cost vs. iterations.

---

## **📝 Example Overview**

The example demonstrates:
- Minimizing the function \( f(x) = (x - 3)^2 + 4 \) (global minimum at \( x = 3 \)).
- Initial guess: \( x_0 = 10 \).
- Cooling rate: 0.95 (temperature decreases by 5% after each iteration).
- Maximum iterations: 1000.

---

## **💡 Feedback and Contact**

If you found this project helpful or have any suggestions, feel free to leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-simulated-annealing) or open an issue in this repository.

---

## **📝 License**

This project is licensed under the MIT License. You are free to use, modify, and share it with attribution.

---

