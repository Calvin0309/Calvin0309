- 👋 Hi, I’m @Calvin0309 , a 20 years old ambitious youth
- 👀 I’m interested in data science.
- 🌱 I’m currently learning statistics.
- 📫 want to reach out to me??  1. Email: lowcheeseng0309@gmail.com 2.IG: calvin_loww01

# **[Project 1: Breast Cancer classifier: Project Overview]** 
For this project I built a breast cancer classifier to predict whether the breast lump is benign or maglinant. This could be useful for the doctors(users) to provide predicted answer to the patients, therefore the patients can decidewhether to carry out further examination or not. 

  1.Users can use the model to make estimation by entering the types/values of 9 features(Clump thickness, uniformity of cell size,	uniformity of cell shape,	marginal adhesion, single epithelial cell size,	bare nuclei,	bland chromatin, normal nucleoli and mitoses). 

  2.To get the best model, I had implement multiple models such as logistic regression, random forest, SVC, XGBoost, CatBoost and so on.

  3.K-fold cross validation is applied to get the most accurate accuracies for each models.

  4.GridsearchCV is used to tune the hyperparameters of each models.

##**Result:**

I had recorded 2 model which gave outstanding performances.

  1.Catboost(accuracy=96.53%, standard deviation= 2.50%, MCC=95.4%, precision= 94.30%, recall= 100%)

  2.Logistic regression (accuracy=97.60%, standard deviation= 1.87%, MCC=90.5% precision= 94%, recall= 94%)

I decided to pick the **Catboost model** since the recall score is perfect (100%) and the MCC is higher. This is because the model is to predict whether the cancer is benign (negative) or maglinant(positive). Thus we want to minimize the false negative (patient actually got maglinant tumor but the predicted result is benign) by having the recall score as high as possible. 

*Dataset= breast_cancer.csv*

*Code=Breast_Cancer_ML_Model.ipynb*

##**Resources** 
The dataset is collected from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)
<!---
Calvin0309/Calvin0309 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
