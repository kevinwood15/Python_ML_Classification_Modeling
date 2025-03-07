# Python_Classification_Modeling
This project uses GaussianNB, Random Forest, and AdaBoost Classification Models to predict the income category of individuals with US Census Data

I pull in the raw data and prepare it by converting all categorical variables into numerical features and normalize all numerical features.
I  split the data into training and test sets, estimate the naive predictor as a baseline, then estimate a GNB, RF, and AdaBoost classication models. 
I then consider performance metrics, prediction/training time, and the algorithms suitability for the data for model selection.
Having chosen the AdaBoost as the best model (best accuracy and F-score with faster computation relative to RF), I tune the parameters for a better fit by varying the number of estimators and learning rates.
Lastly, I examine the features closely and estimate a reduced model using the 5 most important features. This simpler-reduced model has a final Accuracy of 0.86 and an F-score of 0.74. 
