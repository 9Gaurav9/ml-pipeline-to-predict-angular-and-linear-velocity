ML Pipeline for Predicting Cmd_vel_v and Cmd_vel_w

This project implements a machine learning pipeline for predicting the target variables \texttt{Cmd\_vel\_v} (linear velocity) and \texttt{Cmd\_vel\_w} (angular velocity). The entire workflow is organized within a single **Jupyter Notebook** for simplicity, and outputs such as plots and reports are saved to dedicated folders.


Project Structure
- ugaurav_ml_final_code.ipynb: A single Jupyter Notebook that contains all the steps, including preprocessing, training, evaluation, and result visualization.
- plots/: Folder for storing all generated plots, such as learning curves or performance metrics.
- ugaurav_report: Contains the final report summarizing the project and results.

---

Usage
1. Open the ugaurav_ml_final_code.ipynb in Jupyter Notebook or Pycharm.
2. Execute the cells step by step to:
   - Preprocess the data (impute missing values, normalize, and select features).
   - Train the **XGBoost Regressor** for both \texttt{Cmd\_vel\_v} and \texttt{Cmd\_vel\_w}.
   - Evaluate the model using metrics such as **Mean Squared Error (MSE)**.
   - Generate visualizations (e.g., learning curves).
3. Save generated plots and the report in the respective folders.

---

Key Features
- Unified Workflow: The entire pipeline, from preprocessing to evaluation, is encapsulated in a single notebook for simplicity.
- Dual Predictions: The same pipeline is used to predict both \texttt{Cmd\_vel\_v} and \texttt{Cmd\_vel\_w}.
- Performance Metrics:
  - \texttt{Cmd\_vel\_v}: MSE = 0.1168
  - \texttt{Cmd\_vel\_w}: MSE = 0.0715
- Plots: Visual representations, such as learning curves, are stored in the `plots/` directory.
- Comprehensive Report: A detailed summary of the methodology and results is saved in the ugaurav_report.pdf .

---

Prerequisites
- Python Version: 3.8+
- Required Libraries:
  - `pandas`
  - `numpy`
  - `xgboost`
  - `scikit-learn`
  - `matplotlib`
  - `joblib`

Install dependencies using:
a) By storing library names in requirements.txt
__bash
pip install -r requirements.txt
b) pip install <library_name>

---

Author
- Developed by **Gaurav Upadhyay**.

