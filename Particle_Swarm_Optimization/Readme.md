# **Comprehensive Guide to Particle Swarm Optimization (PSO)**

This repository contains a **detailed guide on Particle Swarm Optimization (PSO)** with a Python implementation for solving a **function minimization problem** using **Jupyter Notebook**.

---

## **🔗 Blog Post Reference**

For a comprehensive explanation, read the full blog post:  
[**Comprehensive Guide to Particle Swarm Optimization (PSO)**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-particle-swarm-optimization-pso)

---

## **📁 Project Structure**

- `Particle_Swarm_Optimization.ipynb`: Contains the complete Python implementation, explanations, and visualization of the PSO algorithm.

---

## **🚀 What's Included**

The notebook demonstrates:
1. **PSO Algorithm Overview**:
   - Initialization of particles with random positions and velocities.
   - Update of personal and global best positions.
   - Velocity and position updates based on cognitive and social components.
2. **Example Use Case**:
   - Minimization of the function \( f(x) = (x - 5)^2 \) (global minimum at \( x = 5 \)).
3. **Visualization**:
   - Convergence plot showing the best score over iterations.

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
3. Open `Particle_Swarm_Optimization.ipynb` in the browser and run each cell.

---

## **📊 Performance Metrics**

The notebook evaluates the following:
- **Best Position:** The solution that minimizes the objective function.
- **Best Score:** The minimum value of the objective function.
- **Convergence Plot:** Shows the improvement in the best score over iterations.

---

## **📝 Example Overview**

- **Objective Function:** \( f(x) = (x - 5)^2 \)
- **Initial Search Space:** \( x \in [-10, 10] \)
- **Swarm Size:** 30 particles.
- **Maximum Iterations:** 100.
- **Velocity Update Formula:**
  \[
  v_i(t+1) = w \cdot v_i(t) + c_1 \cdot r_1 \cdot (p_i - x_i(t)) + c_2 \cdot r_2 \cdot (g - x_i(t))
  \]
  where \( w \) is the inertia weight, \( c_1, c_2 \) are acceleration coefficients, and \( r_1, r_2 \) are random values.

---

## **💡 Feedback and Contact**

If you found this project helpful or have suggestions for improvement, feel free to leave feedback on the [**blog post**](https://siddhantbhattarai.hashnode.dev/comprehensive-guide-to-particle-swarm-optimization-pso) or open an issue in this repository.

---

## **📝 License**

This project is licensed under the MIT License. You are free to use, modify, and share it with proper attribution.

---

Let me know if you'd like any edits or additional sections!
