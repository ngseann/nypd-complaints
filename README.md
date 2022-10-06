# nypd-complaints

This project is composed of two Jupyter notebooks:

* `nypd-complaints.ipynb`: This Jupyter notebook contains the deatiled data analysis of a large dataset of complaints made against NYPD officers spanning from 1985 to 2020. After cleaning and doing some exploratory data analysis, some interesting questions arose and were investigated such as looking at whether or not white officer vs. non-white complainants went against complainants. Analysis is supported through a detailed introduction as well as supporitng visualizations.
* `nypd-complaints-model.ipynb`: This Jupyter notebooks uses the same dataset to build some machine learning models used to predict the ethinicity of the complainant. A baseline model of a K-Nearest-Neighbors Classifier was used. That baseline model was then further developed on by carrying out some feature engineering and also comparing different types of classifiers to see which model gave me the best results. I then tested the fairness of my model through permutation tests.
