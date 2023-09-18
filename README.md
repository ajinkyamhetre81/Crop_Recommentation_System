# CROP_RECOMMENDATION_SYSTEM



Crop recommendation is one of the most important aspects of precision agriculture. Crop recommendations are based on a number of factors.
Precision agriculture seeks to define these criteria on a site-by-site basis in order to address crop selection issues.
While the "site-specific" methodology has improved performance, there is still a need to monitor the systems' outcomes.
Precision agriculture systems aren't all created equal. However, in agriculture, it is critical that the recommendations
made are correct and precise, as errors can result in significant material and capital loss.


This application will assist farmers in increasing agricultural productivity, preventing soil degradation in cultivated land,
reducing chemical use in crop production, and maximizing water resource efficiency.
In this application, the user can provide the soil data from their side and the application will predict which crop should the user grow.

## Dataset
This dataset was build by augmenting datasets of rainfall, climate and fertilizer data available for India.

## Attributes information:
* N - Ratio of Nitrogen content in soil
* P - Ratio of Phosphorous content in soil
* K - Ratio of Potassium content in soil
* Temperature - temperature in degree Celsius
* Humidity - relative humidity in %
* ph - ph value of the soil
* Rainfall - rainfall in mm

## Experiment Results:
Performance Evaluation
Splitting the dataset by 80% for training set and 20 % validation set.
Training and Validation
GausianNB with MinMaxScalar gets a higher accuracy score than other classification models.
GaussianNB ( 99 % accuracy score )
Performance Results
Accuracy= 99.3%

## Demo:
![Screenshot (81)](https://github.com/ajinkyamhetre81/CROP_RECOMMENDATION_SYSTEM/assets/114176664/d408e03a-9ec8-40bd-a562-95939e371427)
