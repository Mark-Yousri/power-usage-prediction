# Power-usage-prediction

- This repository contains a Jupyter notebook that demonstrates the application of regression models to predict the power usage of a building based on various features.

- The notebook uses the [UCI Individual household electric power consumption Data Set](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption) as the data source. This data set contains measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years.

- The notebook begins with a comprehensive exploration of the data, including visualizations of the power consumption patterns and correlations between different features. This is followed by preprocessing steps such as handling missing values, outlier detection, and normalization.

- Feature engineering is then performed to create new features that can improve the predictive power of the models. This includes creating time-based features such as hour of the day, day of the week, and month of the year, as well as interaction features that capture the relationships between different original features.

- The notebook applies different regression models including linear regression, ridge regression, lasso regression, and random forest regression. Each model is trained and tuned using cross-validation to find the optimal hyperparameters.

- The performance of each model is evaluated using metrics such as mean absolute error, mean squared error, and root mean squared error. The results are compared and discussed, providing insights into the strengths and weaknesses of each model.

- The notebook concludes with a discussion of potential improvements and future work. This includes ideas for additional feature engineering, trying more complex models, and applying ensemble methods to combine the predictions of multiple models.

