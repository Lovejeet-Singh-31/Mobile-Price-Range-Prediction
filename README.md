# Mobile-Price-Range-Prediction
![image](https://user-images.githubusercontent.com/104754645/204093899-442b103c-ce6a-4c20-a556-20871e1e0d3a.png)
# 📖PROBLEM STATEMENT
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.
# 📖ALGORITHMS USED:
### I. LOGISTIC REGRESSION
### II. Dicision Tree
### III. Random Forest
### IV. Gradient Boosting
### V. XGBOOST
### VI. K-NN
### VII. Support Vector Machine
# 📖Conclusion:
During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'price_range'. also checking the class balance and we found that our target variable is well balanced. Next we analysed categorical variable like, Blue, Three_g, Four_g, Dual_sim, etc, we also analysed numerical variable, found out the distribution and their relationship with the dependent variable to get to know how independent feature effect the price range.
For logestic regression we have to check the multicollinearity. we use VIF Function defined by us.Because the Assumptions of logestic regression says that the multicollinearity of independent variable should not be high.
Rest of the algorithm we use all feature becuase the handles multicollinearity by their own.

We did hyperparameter tuning to improve our model performance using optimal algorithm search tool like GridSearchCV.
* Our target variable is well balanced. There is no class imbalance seen.
* The analysis of the catagorical features like blue(bluetooth), dual_sim, touch_screen and four_g we saw that 50% of the devices has these feature and 50% hasn't.
* The 75% of the devices has feature called three_g.
* when we did analysis of the numerical features like ram, battery_power, px_height and px_width h. we found that higher the ram or battary_power its become more expensive or we can say that these features directly proportional to price_range.
* The distrubution of the most features look like normal distribution.
* we found two feature has outlier so we have to treat them using IQR forluma.
* The accuracy score for logestic regression we got 0.91 on train set and 0.89 for test set by tuning hyperperameter. which is great.
* The Decision Tree Classifier model perform good but over fiitng seen. after tuning some hyper parameter the model slightly improved but not that much..
* The Random forest classifier model perform good but there was some overfiting seen. after tuning hyper parameter the algorithm could not able to reduce overfitng that much.
* The Gradient Boosting Classifier and XGBoost models performs same as random forest classifier.
* The K Nearest Neighbour algorithm perform worst amoung all the algoritms.
* The Support Vector Machine algorithm perform very well after tuning some hyper parameter using optimal algorithm search tool like GridSearchCV.
* The Support Vector Machine with Hyper parameter tuning gives accuracy score on train set is 0.98 and 0.95 on test set which is great. the F1 score is 0.96 on test set.
* the most important features are 'Ram', 'battery_power', 'px_height', 'px_weight' for all the algorithm.
* We can say that SVM model is ready to deploy.
# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.
# 📜 Credits
Lovejeet Singh | Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/lovejeet-singh31/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/Lovejeet-Singh-31) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@lovebanna31) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1JtAYLpo14I_-OEYQ7ylEeST66joC13Cz/view?usp=sharing)

# 📚 References
1. GeekforGeeks

2. Kaggle

3. Analytics Vidya
