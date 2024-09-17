TASK 3 - SALES PREDICTION WITH PYTHON

OBJECTIVE

The aim of this project is to predict sales based on advertising expenditure using the given dataset. The dataset contains information about advertising spending on different platforms (TV, Radio, and Newspaper) and the corresponding sales amount.

LIBRARIES USED

The following important libraries were used for this project:

-numpy
-pandas 
-matplotlib.pyplot 
-seaborn 
-sklearn.model_selection.train_test_split
-sklearn.linear_model.LinearRegression

DATASET

The dataset was loaded using pandas as a DataFrame from the file "sales.csv".

DATA PROCESSING

The shape and descriptive statistics for the dataset were displayed using df.shape and df.describe(). A pair plot was created to visualize the relationship between advertising expenditure on TV, Radio, Newspaper, and sales using seaborn.pairplot. Histograms were plotted to observe the distribution of advertising expenditure on TV, Radio, and Newspaper using matplotlib.pyplot.hist.

ANALYSIS

A correlation matrix heatmap was plotted to observe the correlation between advertising expenditure on TV, Radio, Newspaper, and sales using seaborn.heatmap.

MODEL TRAINING

The data was split into training and testing sets using train_test_split. Linear regression model was trained on the training data using sklearn.linear_model.LinearRegression.

MODEL PREDICTION

The model was used to predict sales based on advertising expenditure on TV for the test set using model.predict(X_test) and the corresponding advertising expenditure on TV in the test set. The model coefficients and intercept were obtained using model.coef_ and model.intercept_. The predictions and actual sales values were plotted using matplotlib.pyplot.plot and matplotlib.pyplot.scatter
