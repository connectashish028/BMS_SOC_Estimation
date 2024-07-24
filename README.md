# BMS_SOC_Estimation

# Intelligent Battery Management System for Optimized State of Charge Estimation

The main objective of the project is to obtain an accurate State of Charge (SOC) for a Lithium Iron Phosphate (LiFePO4 or LFP) battery.

- Maintaining the State of Charge (SOC) within recommended levels is crucial for Lithium Iron Phosphate (LFP) batteries for several reasons:

- Battery Longevity: Proper SOC management extends the lifespan of LFP batteries by reducing stress on cells and minimizing degradation.

- Safety: Monitoring SOC prevents overcharging and over-discharging, ensuring a safe operating environment and preventing hazards.

- Performance Optimization: SOC directly influences energy capacity, ensuring consistent and reliable power output for specific application requirements.

- Efficiency: Optimal SOC levels enhance battery system efficiency, minimizing energy losses and maximizing usable energy.

- Reliability: Consistent SOC management enhances the reliability of LFP batteries, providing users with a stable and predictable energy supply.

Additionally, an accurate State of Charge (SOC) level is essential for Solar Photovoltaic (PV) systems. It helps maintain the battery at a certain level to maximize the next day's PV utilization.

This repository contains a Jupyter Notebook demonstrating improved state of charge (SOC) estimation for a battery management system (BMS) using Python. The project analyzes sensor data, implements a cycle detection algorithm, and corrects for sensor errors.

## Project Overview

This project focuses on enhancing the accuracy of SOC estimation in a BMS. The Jupyter Notebook provides a detailed walkthrough of the following steps:

- **Data Loading and Exploration:** Loading battery data and performing initial exploratory analysis.
- **Cycle Detection:** Implementing an algorithm to identify charge/discharge cycles based on voltage patterns.
- **SOC Calculation:** Calculating SOC using corrected current readings and accounting for coulombic efficiency.
- **Error Correction:** Adjusting for sensor errors and inaccuracies in current measurements.
- **Evaluation:** Comparing the calculated SOC with the BMS-reported SOC to assess the method's effectiveness.

# Data collection

The data has been collected from a home installation battery system using a battery management system (BMS).

The system features a 14 kWh Lithium Iron Phosphate (LFP) battery with an 8s2p configuration, consisting of 16 EVE 280k cells.

Various metrics from the BMS have been stored in InfluxDB over several weeks, allowing for comprehensive monitoring and analysis.

## Getting Started

1. Clone this repository: `git clone <repository_url>`
2. Open the Jupyter Notebook (`BMS_SOC_Estimation.ipynb`) in Google Colab or your preferred environment.
3. Run the code cells sequentially to follow the analysis and implementation steps.

## Libraries Used

- Pandas
- NumPy
- Plotly
- Seaborn
- Matplotlib

## Skills Demonstrated

- Python programming
- Data analysis and visualization
- Battery management systems
- Algorithm development
- Feature engineering
- Data preprocessing
- Model evaluation

## Potential Improvements

- Quantify the evaluation using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- Explore more sophisticated cycle detection algorithms.
- Investigate machine learning techniques for SOC estimation.

## Contributing

Contributions and suggestions for improvement are welcome! Feel free to open issues or submit pull requests.
