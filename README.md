# Machine Learning - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, I created machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Steps

### Preprocessed the Data

* Preprocessed the dataset prior to fitting model.
* Performed feature selection and removed unnecessary features.
* Used `MinMaxScaler` to scale the numerical data.
* Separated the data into training and testing data.

### Tuned Model Parameters

* Used `GridSearch` to tune model parameters.
* Tuned and compared at least two different classifiers.

## Findings

The following machine learning models were used to process the dataset:
* Decision Tree
* K-Nearest Neighbors
* Logistic Regression
* Neural Network
* Random Forest
* Support Vector Machine

After feature selection and tuning the parameters of each model, the Random Forest model classifies candidate exoplanets most accurately. The Random Forest model data score was higher *before* tuning than the other models *after* tuning.

With additional feature selection and parameter tuning, the Random Forest model would be good enough to predict new exoplanets.

### Random Forest
Testing Data Score (after feature selection): **0.9010297482837528**

### Neural Network
Testing Data Score (after feature selection): **0.885011434555**

### Support Vector Machine
Testing Data Score (after feature selection and parmeter tuning): **0.8775743707093822**

### Logistic Regression
Testing Data Score (after feature selection and parmeter tuning): **0.8747139588100686**

### Decision Tree
Testing Data Score (after feature selection and parmeter tuning): **0.8735697940503433**

### K-Nearest Neighbors
Testing Data Score (after feature selection and parmeter tuning): **0.8050734312416555**
