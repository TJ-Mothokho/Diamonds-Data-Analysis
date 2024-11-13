# Diamond Price Prediction Project

## Overview

In this project, I worked with the [Diamond dataset](https://www.kaggle.com/datasets) to predict the price of diamonds based on various features like carat, table, length, width, and depth. The goal was to clean the dataset, explore the data, build simple and multiple linear regression models, and evaluate their performance.

### Project Steps

1. **Data Collection and Cleaning**:
    - The dataset was first loaded and cleaned to handle missing values, duplicate records, and outliers.
    - I explored the relationship between features and target variables using data visualization techniques.
    
2. **Feature Selection**:
    - I performed feature selection to identify the most relevant predictors of the diamond price using various statistical methods like `SelectKBest`.
    - This helped reduce model complexity and improve performance.

3. **Modeling**:
    - I built a **Simple Linear Regression** model to predict diamond prices based on a single feature.
    - Then, I extended the model to **Multiple Linear Regression**, incorporating multiple features like carat, table, length, width, and depth to enhance the prediction accuracy.

4. **Evaluation**:
    - I evaluated the models using metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared** to understand the performance and reliability of the predictions.
    - The models were fine-tuned and validated using train-test splits and cross-validation.

5. **Final Insights**:
    - The models showed a good fit, with the multiple linear regression model providing better predictive accuracy compared to the simple linear regression.
    - The most significant features affecting diamond prices were identified, aiding in a better understanding of the diamond pricing mechanism.

### Technologies Used
- **Python**: For data manipulation, modeling, and visualization.
- **pandas**: For data cleaning and manipulation.
- **numpy**: For numerical operations.
- **scikit-learn**: For building linear regression models and performing feature selection.
- **seaborn & matplotlib**: For data visualization.
  
### Key Files

- `diamond_price_prediction.ipynb`: Jupyter Notebook has the full workflow, from data cleaning to model evaluation.

### Conclusion

This project helped me to apply data preprocessing, feature selection, and linear regression techniques to a real-world dataset. I gained insights into how different features affect diamond pricing, which can be valuable for both machine learning and the jewelry market.
