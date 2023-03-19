# capstone project


1. Loading and understanding the data set
2. Removing irrelevant column
3. Create a label column about loan status
4. Exploratory data analysis
5. Preprocessing of data for another category column
6. Clustering
7. Predicting risk using KNN model
8. Risk prediction using Random Forest
9. Risk prediction using GradientBoost
10. Risk prediction using Neural Network (Keras)

Results 

1. Various models were experimented to predict if the user would pay the debt on time or not. We used binary classification
2. Models used were the KNN model, RandomForest, GradientBoost and Tensor Flow. Couldnt get tensorflow to work since I was missing libraries/ But the code was still written up
3. Random Forest Classifier provided the results in less than half the time (around 6 minutes) compared to KNN model
4. Accuracy of random forest and KNN with 10 neighbours were very similar for test data at around 91%
5. Also tried with increaing number of trees and the accuracy output for test data was not much different 
6. GradientBoost was also comparable to randomforest classifier but the time for training for prediction was one-third of the random forest at just over 2 minutes
7. Tensorflow was used as well and it took 5 minutes to complete with accuracy being similar to other models 
8. Added drop out as an alternative to regularization and the model trained in just over 90 seconds with accuracy of 91% and loss of approx 30%. Both train and test data had similar loss and accuracy. 

Summary:
Keras model with drop out option gave best model with better performance than KNN, Random Forest, Gradient Boost and Keras 

References:

1. https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset?resource=download    
2. https://www.kaggle.com/code/ardhikamalhaq/credit-risk-analysis-using-knn-model 

