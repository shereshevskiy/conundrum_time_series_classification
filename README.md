# <center>Task: Time Series Classification

## Given:
You are given chunks of telemetry data of working equipment (9 sensors, 128 sec) that correspond to 6 different operating modes.
## The task:
1. Analyze data, compute descriptive statistics, perform EDA. Assess data visually and make conclusions on operating models (classes) separability.
2. Perform feature engineering, ideally create features that have clear meaning. Make some comments on created features, e.g. what they mean and how they can help you in the classification task.
3. Predict operating modes of the equipment on the test data (X_test.npy), calculate **precision**, **recall** and **ROC-AUC** on y_test.npy. Develop 2-3 machine learning models, compare and discuss the results.
4. If the score on **any of the metrics** is lower than 0.92 on y_test.npy, then add some new features and aim to make the score above 0.92.
## Form of the delivery:
Please, deliver the solution in the form of a Jupyter notebook where EDA, comments and all the scores can be clearly seen.
