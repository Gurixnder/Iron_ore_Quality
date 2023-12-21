# Iron_ore_Quality
A machine learning model to predict the quality of an iron ore.


The dataset consisits of the features that are crucial in finding the quality of an iron ore.
This Project looks in to the data, analyzes it and then trains a model in order to predict the ore's quality.

# DATA PROCESSING

1. The values of the data are changed from the object data type to float64 in order to be storage efficient.
   Histograms are used to visualize the intitial data.
2. To analyze the data deeply, and understand the correlations among the independent variable and independent variables, correlations among the independent variable     and dependent variable, scatter plots and correlation coefficients are used.
3. Heat map is used to determine the required features for the data.

# Splitting data and Standardiztion

The data is split using train_test_split() method and then the data undergoes the standardization.
Since the dataset has different scales, the standaradization was used used over normalization.

# Training models
There are three models trained in this project, in order to find the best one suited for the job.

Linear Regression, Stochastic Gradient Design(SGD), and Ridge Regression.
After the prediction in each model, mean squared error has been calculated.

Ridge Regression produced the least mean squared error for the system.

# Challenges faced

Since, I am learning machine learnig on my own, it takes me a lot of time and I get confused in my approach sometimes.
The project shows the features I initially used, and not getting a good trained model.
So, I decided to find more relations and analyze data deeper and come to the best suited features.
I had to do some feature engineering and learnt many new things including developing a better approach in tackling a machine learning problem.


