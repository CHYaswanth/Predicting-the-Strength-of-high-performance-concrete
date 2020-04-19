# Predicting-the-Strength-of-high-performance-concrete
This project involved feature exploration and selection to predict the strength of high-performance concrete. Used Regression models like Decision tree regressors to find out the most important features and predict the strength. Cross-validation techniques and Grid search were used to tune the parameters for best model performance.


### Data Description:  
The actual concrete compressive strength (MPa) for a given mixture under a specific age (days) was determined from laboratory. Data is in raw form (not scaled).The
data has 8 quantitative input variables, and 1 quantitative output variable, and 1030 instances (observations).  

### Domain:  
Cement manufacturing  

### Context:   
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include
cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate.  

### Attribute Information:  
* Cement : measured in kg in a m3 mixture  
* Blast : measured in kg in a m3 mixture  
* Fly ash : measured in kg in a m3 mixture  
* Water : measured in kg in a m3 mixture  
* Superplasticizer : measured in kg in a m3 mixture  
* Coarse Aggregate : measured in kg in a m3 mixture  
* Fine Aggregate : measured in kg in a m3 mixture  
* Age : day (1~365)  
* Concrete compressive strength measured in MPa  

### Learning Outcomes:     
* Exploratory Data Analysis  
* Building ML models for regression  
* Hyper parameter tuning  

### Objective:
Modeling of strength of high performance concrete using Machine Learning  

### Steps:
1. Exploratory data quality report reflecting the following:  
    a. Univariate analysis  
        i. data types and description of the independent attributes,     
        ii. analysis of the body of distributions/tails,  
        iii. missing values, outliers  
    b. Multivariate analysis  
        i. analysis between the predictor variables  
        ii. analysis between the predictor variables and target column in terms of their relationship and degree of relation if any.   
        iii. Visualize the analysis using boxplots and pair plots, histograms or density curves.   
      Select the most appropriate attributes    
    c. Pick one strategy to address the presence outliers and missing values and perform necessary imputation  

2. Feature Engineering techniques  
    a. Identify opportunities (if any) to create a composite feature, drop a feature      
    b. Decide on complexity of the model, should it be simple linear model in terms of parameters or would a quadratic or higher degree help?  
    c. Explore for gaussians. If data is likely to be a mix of gaussians, explore individual clusters and present your findings in terms of the independent
attributes and their suitability to predict strength  

3. Create the model  
    a. Obtain feature importance for the individual features       

4. Tuning the model     
    a. Algorithms that will be suitable for this project    
    b. Techniques employed to squeeze that extra performance out of the model without making it overfit or underfit  
    c. Model performance range at 95% confidence level  

### References:  
[Medium article on hyper parameter tuning](https://medium.com/fintechexplained/how-to-fine-tune-your-machine-learning-models-to-improve-forecasting-accuracy-e18e67e58898)
