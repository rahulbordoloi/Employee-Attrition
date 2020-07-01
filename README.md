# Employee-Attrition

Perform EDA on Employee Attrition Dataset and Predict the ones leaving the Company.

This Project is a part of Codepth Data-Science Selection Hackathon.

## Problem Statement -

To Perform Data Analysis on the given dataset and form an insightful report on it. <br>
To Devise a ML Algorithm which will help to predict the employees of comapany who would be leaving and control it acccordingly. <br>

## Technical Goal - 
To find an optimal solution of a Classification Model. <br>

The goal is to find an optimal team of independent variables so that each independent variable of the team has great impact on the dependent variable profits that each independent variable of the team is a powerful predictor that is highly statistically significant. <br>

Perform EDA on the datasets given and take out the insightful analysis for Research. <br>

## Project Insights

According to Detailed Analysis Report, Employees are are working Overtime a Lot, and also have a very less Job Satisfaction are more prone to leave the Company at earliest. Also, there's a pattern followed where employees with less time spent with the company tend to leave the comapany earlier.

Also, Employees who are paid less are observed to be a major factor in attrition. <br>

Extra Insights : Employees from HR tend to leave more, so maybe work atmosphere or leadership issue might be a problem in this case.

A Total of 12 Algorithms are being used here. The Problem Statement given here is a case of Classification Problem as we've to predict an employee that would be leaving the company or not. (Binary Classification). The Different Algorithms being used are -

Classic ML Algorithms : Logistic Regression, Kernel & Linear SVM, K-NN, Naive Bayes. <br>
Tree Based : Decision Tree. <br>
Ensembled Based : Random Forest. <br>
Boosting Algorithms : XGBoost Classifier, GradientBoosting Classifier, AdaBoost Classifier, CatBoost Classifier, LightGBM. <br>

The above Classification Algorithms were been implemented and the model with best performance was worked on (hyperparameter tuning) for further model performance.
Out of all the Algorithms, Random Forest was being selected as being the model with best Performance. It's a Tree Based Ensemble Learning Algorithm which helps us to build a powerful model from the collective perfomances of n-classifing decision sticks improving its perfomance drastically.

## Assumptions -

We make the assumption that the company had given the total database of the employees before attrition.

## Downloads -

*   Problem Statement - [Document Link](https://drive.google.com/file/d/1QpUC9ADne8gCi8nPrwlvEhK8NuDaWTl5/view?usp=sharing)
*   Dataset - [xlsx Link](https://drive.google.com/file/d/14h2JaexZQ2oRH1dt04FvufVu-YVIr0cv/view?usp=sharing)
*   Presentation - [PPT Link](https://drive.google.com/file/d/1eIA9oOhteGD9hkw2fiMSrtnMGRQwlSnu/view?usp=sharing)
*   Libraries Pre-requisites -  [requirements.txt](https://drive.google.com/file/d/1gz-S3CVgvZ5H81hEFlrEBMMcqddBJjsk/view?usp=sharing)        
*   Download Pre-loaded Model -  [Pickle Link](https://drive.google.com/file/d/1EOP91sWILUKdMXzfxbWk9CVODGzhyyWo/view?usp=sharing)
*   Download the iPython Notebook -  [ipynb Link](https://colab.research.google.com/drive/1MZTtt3RuObFuizZeswf4_RAgx9B0ImqL?usp=sharing)

## Usage

To run the project in Local, Clone the Repository and run the following in your terminal -
```
pip install requirements.txt
jupter notebook
```
Then select `Codepth.ipynb` from your directory.

OR

You can directly open `Codepth.ipynb` in Google Colab.
