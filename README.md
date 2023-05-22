# Should This Loan be Approved or Denied?
<strong>Binary Selection</strong>

</center>
<br/>

<h2>Problem Statement</h2>
For this case-study assignment, we assume the role of loan officer at a bank and are asked to approve or deny a loan by assessing its risk of default using 

<br>

<h2>Documents</h2>
Notebooks and Documents are structured thinking about their functional scope:

- **ETL Notebooks**
  - A00 | Dataset Explorations, first observations and Data understanding
  - A01 | Data Sanitizitacion: Outliers and nulls; data imputation, other cleaning techniques
  - A02 | Univariate data analysis
  - A03 | Bivariate data analysis
  - A04 | Time Series and Geographical analysis
  - A05 | Feature engineering, disbalance correction, censored data asumption, other techniques
- **Models**
  - B00 | Regressors Construction and determination of components
    - random tree, xgboost, etc
    - ELI5, LIME, SHAP, Yellowbrick, Alibi, Lucid??
  - B01 | Logistic Regression
    - Early Options Perspective for Available Techniques, Lazy Predict
    - XGBoost
    - Gluon
  - B02 | SVM With Linear and Nonlinear Kernels
    - XGBoost
    - Gluon
  - B03 | Accelerated failure time (AFT) model
    - XGBoost
    - Gluon
  - B04 | Evaluation of regressor: Train, Test and Bootstraping
    - r2, Adjusted R2, RMSE and their stability of results
- **Reports PDFs**
  - Problem Statement
  - Data Report
  - Results Evaluation
  - Problem Presentation

### Other Files:


| file | description |
|-----|-----|
| ./data/appleAppData.json | Raw Data |
| ./data/CleanedData.csv | Cleaned Data |
| ./data/TransformedVars.csv | Feature engineering Data |
| ./data/TestData.csv | Testing Data |
| ./data/TrainData.csv | Training Data |
| ./data/SynData.csv | Bootstraping Data |

### Acknowledgements

```
I couldn't have build this project without the:

  - The gift of learn for free:
      OPEN.ED@PSU, Baja Analytics, MIT OpenCourseWare, geeks for geeks, statweb @Rutgers,
      Google, Analytics vidhya, IBM, The Stats Geek, statisticsbyjim, Coursera and
      a lot more people and teams... Tnx 
      
  - inspiration: Vik Paruchuri @Dataquest
  
  - dataset: @gauthamp10
  
  - Platform: Github
  
  - Software: Jupyter and python
```

### __Notes__  
- The notebooks were worked on a PC win 10, 16 ram and in a
- Bootstrapping a regression model for model evaluation:
  - It is useful to know how much random variation there is in regression coefficients simply because of small changes in data values.
  
### __Author__

 **David Ochoa Corrales**

### Sources and Bibliography:
1. [Machine Learning Applications in Assessing Credit Risk - IMF Working Papers WP/19/109](https://github.com/DavidOchoa-Projects/binary_selection/blob/null_hyp/docs/WPIEA2019109.pdf)
2. [Risk Management Examination Manual for Credit Card Activities Chapter 7 / Federal Deposit Insurance Corporation](https://github.com/DavidOchoa-Projects/binary_selection/blob/null_hyp/docs/ch7.pdf)
3. 


### __License__  

This project is licensed under the next [LICENSE](LICENSE.md)
