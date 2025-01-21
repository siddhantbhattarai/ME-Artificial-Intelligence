The outcomes of the provided Particle Swarm Optimization (PSO) code depend on the configuration, particularly the **objective function**, **number of dimensions**, **number of particles**, and **maximum iterations**.

### Example with Default Settings:

![image](https://github.com/user-attachments/assets/3618072a-3f68-4bf2-892d-9cd7fa99297f)
![image](https://github.com/user-attachments/assets/a57d6c82-75e8-4878-bd97-2b95e135b5a3)

3. **Iteration Logs**:
   - During each iteration, the algorithm prints the current best value.
   - Example (truncated):
     ```
     Iteration 1/100, Best Value: 12.345
     Iteration 2/100, Best Value: 5.678
     Iteration 3/100, Best Value: 0.123
     ...
     Iteration 100/100, Best Value: 0.00001
     ```

4. **Final Output**:
   - Prints the best position and value found:
     ```
     Best Position: [0.001, -0.002], Best Value: 0.000005
     ```

---

### Key Observations:
- **Convergence**:
  - The particles should converge toward the global minimum, guided by their velocities and the \(p_{best}\) and \(g_{best}\) values.
  - For high-dimensional spaces or complex functions, convergence might be slower or may get stuck in local optima.

- **Stochastic Nature**:
  - Results may vary slightly across runs because the algorithm uses random numbers (\(r_1\) and \(r_2\)) in velocity updates.

- **Scalability**:
  - Increasing the number of particles or iterations generally improves accuracy but increases computation time.

---

### How to Modify Outcomes:
1. **Change the Objective Function**:
   - Replace the Sphere function with a different objective function to test PSO on other optimization problems.

2. **Change Bounds**:
   - Modify the bounds to restrict the search space. For example, setting bounds to [\(-5, 5\)] narrows the search area.

3. **Increase Dimensions**:
   - Test in higher-dimensional spaces (e.g., \(dim = 10\)) to explore how PSO handles more complex problems.

4. **Adjust Parameters**:
   - Modify inertia weight (\(\omega\)) and coefficients (\(c_1, c_2\)) to explore their impact on convergence speed and accuracy.
