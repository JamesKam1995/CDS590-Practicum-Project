# CDS590-Practicum-Project
Practicum project under White Room Analytics Pte

The dataset is provided by White Room Analytics. Due to the data sensitivity, there will be no description on the data source. Just a description on how I approach the problem. 

The ppt files shows the methodology applied to resolve to issue. 

## Abstract 
This project uses OBD sensor data including vehicle types, geographical data, engine condition, fuel level and driving behavior to generate a regression model that is capable to forecast the amount of fuel consumption. The objectives of this project are to conduct data exploration to extract insight from the data, to evaluate the factors affecting vehicle fuel consumption and to generate a prediction model of fuel consumption. The result shows that the OBD sensor data is prone to error and intensive data cleaning has to be done. The proposed data cleaning framework is a combination of filtering and clustering method. First outliers in the data are removed and then resampled into 2 minutes interval and clustered to identify the abnormal fuel consumption activity and repair it using linear interpolation method before feeding it into the model. This project also found that geographical data, driving behaviour, fuel activities, distance, speed and battery voltage are the main factors affecting fuel consumption through combination of statistical and feature importance analysis. Prediction models using Random Forest, XGBoost and LightGBM were run and it is found that the Random Forest performs the best with 0.93 of R2 value. There are no overfitting issues happens and it performs consistently under different set of testing data. 

## Data Cleaning framework 
![image](https://github.com/JamesKam1995/CDS590-Practicum-Project/assets/100778004/2ee16d6a-44a9-4ea0-92c8-db54883f6ac4)

