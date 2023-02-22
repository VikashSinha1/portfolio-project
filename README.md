# portfolio-project

The dataset is about laptops configuration with prices containing 1303 laptop data with 12 columns Company name,type namee, laptop size in (inches), Screen resolution, CPU, RAM, Memory, GP, Operating system, Price in INR.

STEPS:- First of all imported necessary libraries for the analysis, imported my dataset into jupiter notebook.Then checked my data for shape, checked null values in the data, checked duplicated values, Did feature engineering on almost all the column, did univariate and bi-variate analysis on the columns for analysis, defined the corelation between Price and independant features, trained my data on all the regression models, got 87% r2_score on Random forest Regressor.  After that used Randomized Seacrh CV for hyperparameter tuning by taking random forest as base model, then used pickle to save my model for further analysis.

INSIGHTS:-
## We can see that most of the laptops are from brand DELL,LENEVO,HP,ASUS,ACER,MSI
#we can see that razer brand has the highest price of laptops among other laptops.
# notebook is the maximum type of laptops among all types
# Workstation and Gaming laptops are the most costly laptops type-wise
# most of the laptops are of 14-16 inches of size
# touchscreen laptops have a higher price as compared to non touchscreen laptops.
#we can see that maximum laptops are  of i7 processors
#i7 processor has the highest price among other processors 
# as the ram increases price also increases. it has a high corelation with price.
## nvidia has the highest price of 80000 then comes intel and then amd
##m MacOs has the highest price as compared to other operating systems
