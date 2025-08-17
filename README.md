# Turbofan Engine Degradation Simulation and RUL Prediction

This repository contains a Python-based simulation for analyzing the degradation of a turbofan engine using machine learning techniques to predict Remaining Useful Life (RUL).

## Overview

The project leverages the **FD001 dataset** from the NASA Turbofan Engine Degradation Simulation dataset, available at the 
[NASA Prognostics Data Repository](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/).

The codebase includes:
- Data preprocessing and feature engineering
- Model training using XGBoost
- Visualization of feature importance

The simulation is implemented in **Jupyter Notebook** and depends on the following libraries:  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, and `joblib`.

The trained model is saved as `fd001_rul_model.pkl` in the `models` directory.


---

## Usage

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install required libraries using the installation commands provided in `main.ipynb`.

3. Download the FD001 dataset from the [NASA repository](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/) and place it in the project directory.

4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook main.ipynb
    ```
   to execute the simulation and visualize results.

---

## Dependencies

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  
- joblib  

---

## Output

- Feature importance plots generated and saved within the notebook.  
- Trained model saved as `models/fd001_rul_model.pkl`.

---

Feel free to open issues or submit pull requests for improvements or questions.
