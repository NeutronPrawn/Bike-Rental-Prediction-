# Bike-Rental-Prediction-

Within this project's scope, our primary objective revolves around training a model to accurately predict the quantity of bike rentals during any given hour throughout the year, based on the prevailing weather conditions. The dataset employed for this purpose has been sourced from the Capital Bikeshare program in Washington, D.C., encompassing a comprehensive historical record of bike usage patterns, along with corresponding weather data, spanning a duration of two years.

Initially, we embark on constructing a multitude of distinct regression models, including Linear, Ridge, Random Forest, Gradient Boost, and Adaboost. Through this approach, we aim to comprehensively explore the intricacies of the dataset and harness the individual strengths of each model. Subsequently, we adopt a sophisticated "Stacking" methodology, wherein the predictions generated by these initial-level models serve as meta-features, effectively enhancing the predictive capabilities of our second-level model. This subsequent model is developed using Linear Regressor, Random Forest, and Gradient Boost techniques, culminating in a refined and more accurate prediction model.

The EDA (Exploratory Data Analysis) and Modeling phases have yielded valuable insights, with notable findings including:

1. The number of bike rentals exhibits a strong correlation with the time of day, with a relatively weaker dependency on temperature and humidity factors.
2. Two distinct rental patterns emerge throughout the day:
   a. On working days, bike rental counts surge during peak office hours (8am and 5pm).
   b. On non-working days, bike rental counts remain relatively steady across the day, peaking around noon.

These key takeaways gleaned from our extensive analysis and modeling efforts provide valuable insights into the complex dynamics of bike rentals, enabling us to develop a robust and accurate prediction model based on the interplay between weather conditions and rental patterns.
