# $Gamma_3^*$
- 
This repository contains code for visualizing the solution region of the inequality \( a + b \geq \log_2(\lceil 2^a \rceil) \) in 2D space using `Matplotlib`. The plot shows the valid region where the inequality holds true for the values of \( a \) and \( b \), with shading and contours.

This repository contains code to generate an interactive 3D plot visualizing vectors and inequalities in a 3D space using Plotly. The vectors are of the form \( h = \lambda_{12}e_{12} + \lambda_{13}e_{13} + \lambda_{123'}e_{123'} \), and the inequalities are represented in terms of tuples \( (\lambda_{12}, \lambda_{13}, \lambda_{123'})_h \) for \( \lambda_j \geq 0 \), where \( j \in \{12, 13, 123'\} \). The gray region represents the inner bound in terms of these tuples, and the vector \( k \), constructed in Proposition 1, is depicted as a red point.

## Matus 2D Inequality Visualization


### Requirements

This project requires the following Python libraries:

- **NumPy**: For numerical calculations.
- **Matplotlib**: For plotting the 2D visualizations.

You can install the required libraries using `pip`:

```bash
pip install numpy matplotlib

![Figure_1](https://github.com/user-attachments/assets/61e131a2-daf2-48cd-b12e-8b73102dcd7e)

## 3D Visualization of Vectors and Inequalities


The code calculates and visualizes the following:

- Valid region where the inequalities are satisfied.
- Boundaries of the inequalities.
- Intersection points between different inequalities.
- Dotted lines that represent various critical data points in the 3D space.
- A specific marked point in the 3D space, highlighted in blue.

## Requirements

To run the code, you need to install the following Python libraries:

```bash
pip install numpy plotly
![newplot](https://github.com/user-attachments/assets/b1734fb6-26ac-4245-8f9c-1056e8c6950f)



