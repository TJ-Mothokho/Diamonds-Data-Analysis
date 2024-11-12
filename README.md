# Diamonds Price Prediction Project

This project utilizes the *Diamonds Dataset* to develop a multiple regression model for predicting diamond prices based on their attributes. With nearly 54,000 entries, this dataset provides a wealth of information for exploring the various factors affecting diamond pricing.

## Dataset Description

The dataset includes prices and other attributes for over 50,000 round-cut diamonds. It consists of 10 variables:

- **price**: Price in US dollars, ranging from $326 to $18,823.
- **carat**: Weight of the diamond, between 0.2 and 5.01.
- **cut**: Quality of the cut, categorized as Fair, Good, Very Good, Premium, and Ideal.
- **color**: Diamond color, rated from D (best) to J (worst).
- **clarity**: Clarity of the diamond, from I1 (worst) to IF (best).
- **x**: Length in mm, ranging from 0 to 10.74.
- **y**: Width in mm, ranging from 0 to 58.9.
- **z**: Depth in mm, from 0 to 31.8.
- **depth**: Total depth percentage, calculated as `2 * z / (x + y)` with a range of 43 to 79.
- **table**: Width of the top of the diamond relative to the widest point, ranging from 43 to 95.

## Project Overview

### Objective
The goal of this project is to predict the **price** of diamonds based on their physical and qualitative attributes using a multiple regression model.

### Steps Taken
1. **Data Cleaning**: Identified and handled any missing or outlier values.
2. **Exploratory Data Analysis (EDA)**: Explored relationships between features and the price to inform feature selection.
3. **Feature Engineering**: Created or transformed variables as needed.
4. **Model Selection**: Tested various regression models, selecting the most appropriate one based on performance metrics.
5. **Model Evaluation**: Assessed model accuracy using R², adjusted R², and Mean Absolute Error (MAE).
6. **Interpretation**: Analyzed the impact of each feature on price to derive insights.

### Results
The final model provided accurate predictions for diamond prices, with key features (e.g., carat, cut, and clarity) playing a significant role in determining value.

## Conclusion

This project demonstrates how multiple regression can be used to predict diamond prices based on various physical and qualitative characteristics. Through the insights gained, this model provides an understanding of the primary factors influencing diamond pricing.

## Future Work

- Test additional models like random forests or gradient boosting for potential improvement.
- Experiment with feature interactions and polynomial regression for non-linear relationships.

## Acknowledgments

This project utilizes the *Diamonds Dataset* available at `R/data.R`, which includes pricing and other relevant attributes.


