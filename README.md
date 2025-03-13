# Gamma_3

## Matus 2D Inequality Visualization



## 3D Visualization of Vectors and Inequalities

This repository contains code to generate an interactive 3D plot visualizing vectors and inequalities in a 3D space using Plotly. The vectors are of the form \( h = \lambda_{12}e_{12} + \lambda_{13}e_{13} + \lambda_{123'}e_{123'} \), and the inequalities are represented in terms of tuples \( (\lambda_{12}, \lambda_{13}, \lambda_{123'})_h \) for \( \lambda_j \geq 0 \), where \( j \in \{12, 13, 123'\} \). The gray region represents the inner bound in terms of these tuples, and the vector \( k \), constructed in Proposition 1, is depicted as a red point.

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
