# Machine Learning - Exoplanet Exploration

## Aim

To develop machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Data source

https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results

## Method

- Remove unnecessary columns and null rows.
- Preprocess data using standardscaling / minmaxscaling / PCA.
- Tune model parameters with gridsearch.
- Experiment with various algorithms to develop a model with high accuracy score. 

## Models used
- SVM (minmax scaler)
![SVM_minmax_scale.png](Images/SVM_minmax_scale.PNG) 

- SVM (standard scaler)
![SVM_standard_scale.png](Images/SVM_standard_scale.PNG) 

- Random forest
- SVM (minmax scaller)
![random_forest.png](Images/random_forest.PNG) 

## Finding
- Random forest model has the highest accuracy score (accuracy of 90%). 
- With SVM model, scalling data using standard scaller produces more accurate model compared to minmax scaller (accuracy of 81% vs 88%).
- All models predict "false positive" category most accurately.
- All models predict "candidate" category with the least accuracy. 