Insurance Claim Prediction

This project uses machine learning to predict whether an individual is likely to make an insurance claim based on demographic and health-related data. The dataset includes both features and a binary target label indicating insurance claim status.

Dataset Overview

The dataset contains the following columns:
- age: Age of the insured person
- sex: Gender (male/female)
- bmi: Body Mass Index
- children: Number of children covered by insurance
- smoker: Smoking status (yes/no)
- charges: Medical charges billed to the insurance
- insuranceclaim: Target variable – whether an insurance claim was made (0 or 1)

> *Note*: The dataset is loaded from a local zip archive.

 Machine Learning Models Used

Classification Models
These models predict whether an insurance claim will occur (binary classification):

1. K-Nearest Neighbors (KNN)
2. Decision Tree Classifier
3. Random Forest Classifier

Metric Used: 
Accuracy Score

 Regression Model
Although the task is classification, a Linear Regression model was also applied (for exploration).

Metrics Used:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

  Libraries Used
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KNN, Decision Tree, Random Forest, Linear Regression, metrics)

Visualizations
The class distribution (insuranceclaim) is plotted using Seaborn's countplot, with a hue of charges to examine how charges vary by claim status.

How to Run the Code

1. Install required libraries:
   bash
   pip install pandas numpy matplotlib seaborn scikit-learn

conclusion:
  This project successfully trains a classification model to predict insurance claims.
  Random Forest performs well for this use case.
  The model can now accept user input and make real-time predictions.
