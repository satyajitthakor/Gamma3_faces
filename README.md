# Matus 2D Inequality Visualization & 3D Vector Plotting

This repository contains code for visualizing the solution region of the inequality $a + b \geq \log_2(\lceil 2^a \rceil)$ in 2D space using `Matplotlib`. The plot shows the valid region where the inequality holds true for the values of $a$ and $b$, with shading and contours.

Additionally, this repository includes code to generate an interactive 3D plot that visualizes vectors and inequalities in 3D space using `Plotly`. The vectors are of the form:

$$
h = \lambda_{12} e_{12} + \lambda_{13} e_{13} + \lambda_{123'} e_{123'}
$$

The inequalities are represented in terms of the tuples $(\lambda_{12}, \lambda_{13}, \lambda_{123'})_h$ for $\lambda_j \geq 0$, where $j \in \{12, 13, 123'\}$. The gray region represents the inner bound in terms of these tuples, and the vector $k$ (referenced in Proposition 1 of our paper) is depicted as a red point.

## Matus 2D Inequality Visualization

This section visualizes the solution to the inequality $a + b \geq \log_2(\lceil 2^a \rceil)$ in 2D.

### Requirements

This project requires the following Python libraries:

- **NumPy**: For numerical calculations.
- **Matplotlib**: For plotting the 2D visualizations.

You can install the required libraries using `pip`:

```bash
pip install numpy matplotlib


