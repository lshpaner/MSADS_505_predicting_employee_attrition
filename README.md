<p align = "center">
  <img src="https://github.com/MSADS-505-Data-Science-for-Business/predicting_employee_attrition/blob/main/attrition.png">
</p>

# Predicting Employee Attrition: A Human Resources Solution

This project is a part of the ADS-505 course in the Applied Data Science Program at the University of San Diego. 

### Project Status: Completed

### Installation

To use this project, first clone the repo on your device using the commands below:

`git init`

`git clone https://github.com/MSADS-505-Data-Science-for-Business/predicting_employee_attrition.git`

### Project Intro/Objective

Our endeavor is to build a sustainable system-wide business-model with predictive analytics to solve a universal human resources problem: employee attrition. The goal is to classify employee attrition for an undisclosed multinational corporation (MNC). The corporation has provided an Excel (.xlsx) file for academic research in people analytics. However, the use-case can be extended to practical human resource problem-solving methods. This data mining project was carried out in Python using Jupyter Notebook.

People analytics traditionally benefits from "using statistical insights from employee data to make talent management decisions" (Leonardi & Contractor, 2018). Gathering historical information on employees' performance, promotional patterns, and length of time served are valuable tools that do not establish trajectories that can be useful in a decision-making framework. Employee attrition costs the company time, money, and resources. The company bleeds money when retention is not optimum, thus investing money into something that is not used or useful drains the company's bottom line. To this end, we will provide tools and technologies to resolve retention for this MNC. The impact of this project is to predict employee attrition and benefit the MNC from losing money and resources.

### Partner(s)/Contributor(s) 

* [Leonid Shpaner](https://www.leonshpaner.com)
* [Payal Bhavesh Muni](https://github.com/orgs/MSADS-505-Data-Science-for-Business/people/munipayal1)
* [Sean Torres](https://github.com/orgs/MSADS-505-Data-Science-for-Business/people/seantorres)

### Methods Used
* Inferential Statistics
* Data Mining
* Predictive Modeling
* Machine Learning
* Data Visualization
* Data Engineering
* Programming
* Data Manipulation
* Case Study 

### Technologies
* Python 
* Microsoft Excel
* Microsoft PowerPoint

### Project Description
The dataset is sourced from Kaggle. It consists of 11 features and 14,999 rows of employee data. The first three features are 'employee id', 'satisfaction_level', and 'last_evaluation.' This is followed by 'Number_project', 'average_monthly_hours', and 'time_spend_company.' The remaining predictors are 'work_accident', 'promotion_last_5years', 'department', and 'salary'. The target (outcome) variable is 'left' – used to predict employee attrition. 

Hypotheses:   

Null: There is no difference in attrition from the original dataset and validated dataset.    
Alternative: There is a difference in attrition from the original dataset and validated dataset.

**Data Analysis, Visualization, and Modeling**  
For exploratory data analysis, we check the distribution of data using boxplots and histograms. Additionally, we check for multicollinearity using a correlation matrix.

For modeling, the following are used:
* Logistic Regression
* Decision Trees
* Support Vector Machines
* Random Forests
* Bagging
* Linear Discriminant Analysis
* Neural Networks
* *K*-Nearest Neighbors

The visualizations for the models include: 
* Confusion Matrices
* Cumulative Gains Charts
* Receiving Operating Characteristic (ROC) Curve
* Area Under the Curve (AUC)
* Summary Tables

Roadblocks/ Challenges:
* Deciding on optimal methods for determining hyperparameters
* Hyperparameter tuning may not always yield expected results
* Determining the ideal train_test_valid split due to dataset size

### License
MIT License
Copyright (c) 2018
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Acknowledgements
Thank you Dr. Tarshizi and Professor Malin for your guidance in facilitating this project. Moreover, thank you to everyone involved as contributors to this repository.

### References
Leonardi, P. & Contractor, N. (2018). Better People Analytics. Harvard Business Review. 
&nbsp;&nbsp;&nbsp;&nbsp; https://hbr.org/2018/11/better-people-analytics
