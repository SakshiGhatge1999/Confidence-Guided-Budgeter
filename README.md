Confidence-Guided Budgeter (CGB)- A hybrid machine learning framework designed to balance predictive accuracy with interpretability in financial decision-making systems.

Overview 
The CGB system arbitrates between an interpretable Logistic Regression model and a high-accuracy Random Forest classifier. By using calibrated confidence estimates, the framework ensures that complex models are only utilized when they exhibit high certainty, defaulting to transparent decision logic otherwise.

Key Results
Optimal Threshold (tau): 0.88.
Trust Reliance Ratio (TRR): 72.2% of decisions were made by the interpretable model.
Hybrid Accuracy: 70.9% on the final test set.
Statistical Validation: Paired t-test p-value of 4.26e-08 (p < 0.05).

Installation
Clone the repository: git clone https://github.com/SakshiGhatge1999/Confidence-Guided-Budgeter.git

Install required dependencies: pip install -r requirements.txt

How to Run
Ensure german_credit_data.csv is in the same directory as the notebook.
Open Confidence-Guided Budgeter .ipynb in a Jupyter environment.
Select "Run All" to reproduce the preprocessing, calibration, and arbitration experiments.

Repository Structure
Confidence-Guided Budgeter .ipynb: Main implementation and experimental results.
german_credit_data.csv: Statlog (German Credit) dataset.
requirements.txt: List of Python libraries required for reproducibility.
