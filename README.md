Wire EDM Process Parameter Optimization using Machine Learning
📌 Project Overview

This project focuses on optimizing process parameters of Wire EDM (Electrical Discharge Machining) using Machine Learning.
I trained and compared multiple models (Polynomial Regression, Decision Tree, Random Forest) on experimental data (RSM-CCD based DOE).
Polynomial Regression (degree 2) achieved the best performance with the highest R² score and minimum MSE.
Further, Bayesian Optimization and Multi-Objective Optimization were applied to improve predictions for:

MRR (Material Removal Rate)

Surface Roughness (Ra)

🧠 Features

Predicts optimized Wire EDM parameters given the work material.

Uses RSM-CCD DOE data for training.

Multi-objective optimization to balance MRR, Ra, and energy consumption.

Compares different ML models and reports performance metrics.

🛠️ Tech Stack

Language: Python

Libraries: scikit-learn, pandas, numpy, matplotlib, optuna

Environment: Jupyter Notebook (.ipynb)

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Install dependencies:

pip install -r requirements.txt
Open the Jupyter Notebook:
jupyter notebook
Run the cells step by step to train and evaluate models.

📊 Results

Polynomial Regression (Degree 2) performed best (highest R², lowest MSE).

Bayesian Optimization suggested parameter ranges that maximize MRR while minimizing Ra.

Multi-objective plots show trade-offs between MRR and Ra for better decision-making.

🔮 Future Scope

Integrate real-time feedback from CNC Wire EDM machine for adaptive learning.

Automate geometric complexity extraction from CAD files as model input.

Deploy as a web app for easy parameter prediction.
 file for details.

Would you like me to prepare a requirements.txt file for your project as well (so others can easily install the depende
