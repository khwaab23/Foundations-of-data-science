# Causal Impact of Weather on Food Delivery Times

## Overview

This project investigates how weather conditions causally affect food delivery durations, accounting for traffic density as a confounding variable. By exploring these relationships, the analysis offers practical insights to help optimize delivery operations during varying weather and traffic conditions.

## Research Objective

To determine the extent to which different weather conditions impact delivery times and how traffic density mediates or confounds this relationship.

## Dataset

- Sourced from Kaggle with 100+ samples, covering:
  - **Delivery Time (mins)**
  - **Weather Conditions**: Sunny, Cloudy, Fog, Stormy, Sandstorms, Windy
  - **Traffic Density**: Low, Medium, High

## Approach

- Built **causal DAG models** representing direct and indirect effects.
- Used **Bayesian statistical modeling** to estimate total and direct effects.
- Performed **prior predictive checks and posterior diagnostics** using PyMC and ArviZ.
- Compared models using **PSIS-LOO cross-validation** for predictive performance assessment.
- Visualized results with Matplotlib and Seaborn.

## Key Findings

- Sunny weather generally reduces delivery times, while storms, fog, and sandstorms increase delays, particularly under high traffic.
- Traffic density acts as a confounder and mediator, influencing the magnitude of weather effects on delivery times.
- The **direct effect model outperformed** the total effect model in predictive accuracy.
- Posterior predictive checks confirmed the models align well with observed data.

## Technologies Used

- Python
- Pandas, NumPy
- PyMC, ArviZ
- Matplotlib, Seaborn
- NetworkX (for DAG visualization)
- Jupyter Notebook

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/causal-weather-delivery.git
    cd causal-weather-delivery
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook
    ```
    Run all cells in the notebook to reproduce the analysis, models, and visualizations.

## Future Scope

- Hierarchical modeling across geographic zones.
- Advanced causal mediation analysis.
- Integration of additional features such as time of day and distance buckets.
- Building a real-time prediction dashboard for delivery optimization.

## Team

- **Aranya Aryaman**
- **Khwaab Thareja**
- **Ishaan Mishra**


