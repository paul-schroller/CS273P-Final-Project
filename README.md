# 273P-Final-Project
Using Neural Networks to generate monthly probabilistic earthquake forecasts across the globe given the previous 6 months of earthquake data.

Setup: download the 273p_final_project.ipynb and the database.csv (I provide the database.csv here, but it can originally be downloaded from https://www.kaggle.com/datasets/usgs/earthquake-database/data)

Required dependencies: numpy, pandas, matplotlib, seaborn, torch, sklearn.

Run all code cells in the notebook sequentially to prepare the data, train the first model, evaluate the first model, train the second model, evaluate second model, train the third model, and then evaluate the third model.

I originally ran this in a Google Colab notebook on a cloud runtime hosted on a T4 GPU, so that would be the ideal way to run it. If it is run in this way, the first and second model should take about 10-15 minutes each to train, and the third model takes about 45 minutes to train.
