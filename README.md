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

* Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

The following machine learning models were used to process the dataset:
* Decision Tree
* K-Nearest Neighbors
* Logistic Regression
* Neural Network
* Random Forest
* Support Vector Machine

After feature selection and tuning the parameters of each model, the Random Forest model classifies candidate exoplanets most accurately. The Random Forest model data score was higher before tuning than the other models after tuning.

###Decision Tree
0.847254004576659
Testing Data Score: 0.8735697940503433

###K-Nearest Neighbors
0.8050734312416555

###Logistic Regression
0.816933638443936
0.8747139588100686

###Neural Network
Accuracy: 0.885011434555

###Random Forest
0.897025171624714

###Support Vector Machine
0.8260869565217391
0.8775743707093822





