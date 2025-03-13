# \(\Gamma_3^*\)

This repository contains code for visualizing the solution region of the inequality:

\[
a + b \geq \log_2(\lceil 2^a \rceil)
\]

in 2D space using Matplotlib. The plot highlights the valid region where the inequality holds true for values of \( a \) and \( b \), with appropriate shading and contours.

Additionally, this repository provides an interactive 3D plot for visualizing vectors and inequalities in a 3D space using Plotly. The vectors are of the form:

\[
h = \lambda_{12}e_{12} + \lambda_{13}e_{13} + \lambda_{123'}e_{123'}
\]

where the inequalities are represented as tuples:

\[
(\lambda_{12}, \lambda_{13}, \lambda_{123'})_h, \quad \lambda_j \geq 0, \quad j \in \{12, 13, 123'\}.
\]

The gray region represents the inner bound for these tuples, while the vector \( k \) (referenced in Proposition 1 of our paper) is depicted as a red point.

---

## **Matus 2D Inequality Visualization**

### **Requirements**

This project requires the following Python libraries:

- **NumPy**: For numerical calculations.  
- **Matplotlib**: For plotting the 2D visualizations.  

Install them using:

```bash
pip install numpy matplotlib
```

### **Figure**

![Figure 1](https://github.com/user-attachments/assets/259ed0d1-76ac-46db-987f-e59e6b2309a3)

---

## **3D Visualization of Vectors and Inequalities**

The code calculates and visualizes:

- The valid region where inequalities hold.  
- Boundaries of the inequalities.  
- Intersection points between different inequalities.  
- Dotted lines representing critical data points in 3D space.  
- A specific marked point in 3D space, highlighted in blue.  

### **Requirements**

To run the 3D visualization, install the following:

```bash
pip install numpy plotly
```

### **Figure**

![3D Plot](https://github.com/user-attachments/assets/ed42b6d2-e139-46a5-8c1e-fbc3071772fa)

---

### **Usage**

Run the 2D visualization:
```bash
python matus_2d_plot.py
```

Run the 3D visualization:
```bash
python vector_inequality_3d.py
```

For any issues, feel free to open an issue or contribute to the repository! 🚀
