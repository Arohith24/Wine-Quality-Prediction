# Azure Wine-Quality-Prediction
**PROJECT STATEMENT**

The dataset is related to the red variant of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).These datasets can be viewed as regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones). 


**PROBLEM DEFINITION** 

This project aims to determine which chemical features are the best quality red wine indicators. To be more specific, we define below problems for this analysis:
Show the contribution of each factor to the wine quality in this model.
Show which features are more important in determining the wine quality.
Show which features are less important in determining the wine quality As mentioned earlier, our target variable will be wine quality, which is scored between 3 and 8.
the output  varies from low to high. Low category contains wines whose quality is 3 or 4, Medium category contains wines whose quality is 5 or 6, High category wines whose quality is 7 or 8.


**DASET AND DATA INFORMATION**

The datatset contains of 1599 rows and 12 coloumns where each feature contributes it part in the preparation of the wine. The information about the features is given below 

* FIXED ACIDITY:  most acids involved with wine or fixed or nonvolatile (do not evaporate readily).

* VOLATILE ACIDITY: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.

* CITRIC ACID: found in small quantities, citric acid can add 'freshness' and flavor to wines.

* RESIDUAL SUGAR: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.

* CHLORIDES: the amount of salt in the wine.

* FREE SULPHUR DIOXIDE: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.

* TOTAL SULPHUR DIOXIDE: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine.

* DENSITY: the density of wine is close to that of water depending on the percent alcohol and sugar content.

* pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale.

* SULPAHTES: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant.

* ALCOHOL: the percent alcohol content of the wine.

* QUALITY: output variable (based on sensory data, score between 0 and 10).

Output variable (based on sensory data): quality (score between 3 and 8).


**WHY LINEAR REGRESSION**

 Linear regression because regression analysis allows us to understand the strength of relationships between variables. And regression analysis tells you what predictors in a model are statistically significant and which are not. In simpler terms, if given a regression model of 50 features, one can find out which features are good predictors for the target variable and which aren’t.Regression analysis can give a confidence interval for each regression coefficient that it estimates. Not only can you estimate a single coefficient for each feature, but you can also get a range of coefficients with a level of confidence (e.g., 99% confidence) that the coefficient is in.


**CONCLUSION**

The interest has been increased in the wine industry in recent years which demands growth in this industry. Therefore, companies are investing in new technologies to improve wine(production and selling) quality. In this direction, wine quality certification plays a very important role for both processes and it requires wine testing by human experts. The work done in this experiment  will explore the usage of machine learning techniques. How linear regression determines the important features for prediction and how we used other methods and functions to predict the values. The benchmark dataset of Red wine is used, which contains 1599 rows x 12 columns of data samples. The dataset contains 12 physicochemical characteristics. This experiment shows that the dependent variable can be predicted more accurately if only important features are considered in the prediction rather than considering all features. In the future, Large datasets can be taken for experiments and other machine learning techniques may be explored for wine quality prediction. The project is done on MICROSOFT AZURE MACHINE LEARNING STUDIO which is a cloud based machine learning platform which is a part of Cortana Analytics Suite,where one could build experiments through just drag and drop method  and the experiments can be published to azure gallery.This studio has wide range of applications, where one can use different machine learning techniques to build experiments in a more precise manner,it can also deploy a webservice,and all of this can be done withot a single piece of code.    





