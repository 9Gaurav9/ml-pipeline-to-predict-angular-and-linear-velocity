# ML Pipeline for Predicting Cmd_vel_v and Cmd_vel_w

This project implements a machine learning pipeline designed to predict the target variables **Cmd_vel_v** (linear velocity) and **Cmd_vel_w** (angular velocity) in a robotic control system. The workflow is organized in a single **Jupyter Notebook** for simplicity and efficiency, with outputs such as plots and reports being saved in dedicated directories.

## Project Structure

- `ugaurav_ml_final_code.ipynb`: A Jupyter Notebook that contains the complete machine learning pipeline, including data preprocessing, training, evaluation, and result visualization.
- `plots/`: A directory where all generated plots (e.g., learning curves, performance metrics) are stored.
<!-- `ugaurav_report.pdf`: A detailed report summarizing the methodology, results, and insights from the project. -->

## Usage

1. Open the `ugaurav_ml_final_code.ipynb` in Jupyter Notebook or PyCharm.
2. Execute the notebook cells step by step:
   - **Preprocessing**: Impute missing values, normalize data, and perform feature selection.
   - **Model Training**: Train the **XGBoost Regressor** model for predicting both `Cmd_vel_v` and `Cmd_vel_w`.
   - **Model Evaluation**: Evaluate the model's performance using metrics such as **Mean Squared Error (MSE)**.
   - **Visualization**: Generate visualizations like learning curves and performance charts.
3. The generated plots will be saved in the `plots/` directory, and the final report will be stored as `ugaurav_report.pdf`.

## Key Features

- **Unified Workflow**: The entire machine learning pipeline is encapsulated in a single Jupyter Notebook, providing an easy-to-follow, reproducible workflow.
- **Dual Predictions**: The same pipeline is utilized to predict both `Cmd_vel_v` and `Cmd_vel_w`, allowing for efficient and accurate control of linear and angular velocities.
- **Performance Metrics**:
  - `Cmd_vel_v`: Mean Squared Error (MSE) = **0.1168**
  - `Cmd_vel_w`: Mean Squared Error (MSE) = **0.0715**
- **Visualization**: Plots, such as learning curves and performance metrics, are saved in the `plots/` folder for easy access and review.
- **Comprehensive Report**: A detailed PDF report summarizing the methodology, results, and analysis is provided in the `ugaurav_report.pdf`.

## Prerequisites

- **Python Version**: 3.8+
- **Required Libraries**:
  - `pandas`
  - `numpy`
  - `xgboost`
  - `scikit-learn`
  - `matplotlib`
  - `joblib`

### Installation

To install the required dependencies, you can use one of the following methods:

1. **Using `requirements.txt`**:
   - Create a `requirements.txt` file with the necessary libraries and run:
     ```bash
     pip install -r requirements.txt
     ```

2. **Installing Libraries Individually**:
   - Alternatively, you can install each library individually using:
     ```bash
     pip install <library_name>
     ```

## Author

- **Gaurav Upadhyay**: Developed and maintained the project.
