# $\Gamma_3^*$

## 3D Visualization of Vectors and Inequalities

The code calculates and visualizes the following:

- Valid region where the inequalities are satisfied.
- Boundaries of the inequalities.


### Requirements

To run the code, you need to install the following Python libraries:

```bash
pip install numpy plotly
```


### Interactive 3D Plots

Click the link below to view the interactive 3D plot:
#### For face ($\lambda_{123'}, \lambda_{12}, \lambda_{13}$):

[![📊 View 3D Plot](https://img.shields.io/badge/Open-3D%20Plot-blue?style=for-the-badge)](https://satyajitthakor.github.io/Gamma_3/interactive_3D_plot.html)

A zoomed projection of the above 3D plot is shown here:
![newplot (6)](https://github.com/user-attachments/assets/c2c13f91-92a2-4768-9d93-867a848d75b3)

To reproduce the plot, run:
```bash
python 3D_visualization.ipynb
```


#### For face ($\lambda_{123'}, \lambda_{12}, \lambda_{1}$) (Matus Inequality-based):
[![📊 View 3D Plot](https://img.shields.io/badge/Open-3D%20Plot-blue?style=for-the-badge)](https://satyajitthakor.github.io/Gamma_3/interactive_3D_plot_12_123.html)

A zoomed projection of the above 3D plot is shown here:
![newplot (7)](https://github.com/user-attachments/assets/d7e44b07-4699-4ce3-b634-ba51521e07d3)

To reproduce the plot, run:
```bash
python 3D_vis_12_1_123.ipynb
```

#### For face ($\lambda_{123'}, \lambda_{12}, \lambda_{1}$) (Not Matus Inequality-based, i.e., $\lambda_{123'} = log_2(M), M \in \mathbb{N}$):
[![📊 View 3D Plot](https://img.shields.io/badge/Open-3D%20Plot-blue?style=for-the-badge)](https://satyajitthakor.github.io/Gamma_3/interactive_3D_plot_log2M_1_2_3_4.html)

A zoomed projection of the above 3D plot is shown here:
![newplot (14)](https://github.com/user-attachments/assets/198ce710-675e-4587-b573-687f7ec23118)

To reproduce the plot, run:
```bash
python 3D_vis_12_1_123.ipynb
```




## Matus 2D Inequality Visualization

### Requirements

This project requires the following Python libraries:

- **NumPy**: For numerical calculations.
- **Matplotlib**: For plotting the 2D visualizations.

You can install the required libraries using pip:

```bash
pip install numpy matplotlib
```

![Figure_1](https://github.com/user-attachments/assets/259ed0d1-76ac-46db-987f-e59e6b2309a3)
To reproduce the plot, run:
```bash
python 2D_Matus_Visualization.ipynb
```
