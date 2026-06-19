# california-housing-linear-regression
What's in this folder
task1_ml_linear_regression.ipynb - main notebook with data loading, EDA, model training and plots
task1_ml_report.pdf - short writeup of the work
actual_vs_predicted.png and residuals_plot.png - graphs from the notebook
house_price_model.pkl - saved model
predict_ui.py - small script to test a prediction
requirements.txt - libraries needed to run the notebook
# Setup
Make sure Python 3 is installed, then run:

pip install -r requirements.txt
Running the notebook
Open the ipynb file in Jupyter and run the cells top to bottom.

jupyter notebook task1_ml_linear_regression.ipynb
Prediction script
After the model is saved from the notebook, you can run:

python predict_ui.py
It will ask for the 8 feature values. You can also pass them directly:

python predict_ui.py 3.5 20 5.0 1.0 1500 3.0 34.05 -118.25
# Results
On the test set the model gave:

MAE: 0.533
RMSE: 0.746
R2: 0.576
MedInc had the strongest link with price, which makes sense. The model works as a basic baseline but higher priced homes are harder to predict.

Author
Parth Khairkar
