# BMS_SOC_Estimation

# Intelligent Battery Management System for Optimized State of Charge Estimation

This repository contains a Jupyter Notebook demonstrating improved state of charge (SOC) estimation for a battery management system (BMS) using Python. The project analyzes sensor data, implements a cycle detection algorithm, and corrects for sensor errors.

## Project Overview

This project focuses on enhancing the accuracy of SOC estimation in a BMS. The Jupyter Notebook provides a detailed walkthrough of the following steps:

- **Data Loading and Exploration:** Loading battery data and performing initial exploratory analysis.
- **Cycle Detection:** Implementing an algorithm to identify charge/discharge cycles based on voltage patterns.
- **SOC Calculation:** Calculating SOC using corrected current readings and accounting for coulombic efficiency.
- **Error Correction:** Adjusting for sensor errors and inaccuracies in current measurements.
- **Evaluation:** Comparing the calculated SOC with the BMS-reported SOC to assess the method's effectiveness.

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
