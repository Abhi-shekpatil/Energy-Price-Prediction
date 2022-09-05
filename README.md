# Energy-Price-Prediction
prediction of actual price of energy

The dataset has been an aggregated collection of features relating to different type of energies by production method.

DATASET (Columns)

'time', 'generation biomass', 'generation fossil brown coal/lignite',
 'generation fossil coal-derived gas', 'generation fossil gas',
 'generation fossil hard coal', 'generation fossil oil',
 'generation fossil oil shale', 'generation fossil peat',
 'generation geothermal', 'generation hydro pumped storage aggregated',
 'generation hydro pumped storage consumption',
 'generation hydro run-of-river and poundage',
 'generation hydro water reservoir', 'generation marine',
 'generation nuclear', 'generation other', 'generation other renewable',
 'generation solar', 'generation waste', 'generation wind offshore',
 'generation wind onshore', 'forecast solar day ahead',
 'forecast wind offshore eday ahead', 'forecast wind onshore day ahead',
 'total load forecast', 'total load actual', 'price day ahead',
 'price actual'
 
different Exploratory Data Analysis tools have been deployed with proper null value handling. Dropping irrelevant columns and applied scaling. fitting 7 different machine learning models ie. Linear Regression, Decision Tree, Random Forest Regressor, K-Nearest Neighbor, Support Vector Machine and, Artificial Neural Network(MLP).
 
Random Forest regressor had highest training accuracy of 98.166% with a test accuracy of 86.81%. It seems to be a case of overfitting. meanwhile comparatively relevant accuracy for both test and training data i.e. 86.387% and 91.95% resp was given by KNN model.
