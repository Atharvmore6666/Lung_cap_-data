# Lung_cap_-data
This project predicts lung capacity using linear regression on the LungCapData dataset. After encoding categorical data and splitting the dataset, evaluation metrics like R-squared, MSE, RMSE, and MAPE assess accuracy. Visualizations show error distribution and prediction trends.

# Lung Capacity Prediction


## Dataset
The dataset `LungCapData.csv` contains the following columns:

| Column            | Data Type       | Description                                |
|-------------------|-----------------|--------------------------------------------|
| Age               | Integer         | Age of the individual                      |
| Height            | Float           | Height of the individual                   |
| Gender            | Object (Encoded)| Gender of the individual                   |
| Smoke             | Object (Encoded)| Smoking status                             |
| LungCap           | Float           | Measured lung capacity                     |

## Motivation
Lung capacity is a vital health indicator influenced by factors like age, height, and smoking status. By accurately predicting lung capacity, this model can serve as a tool for healthcare analysis, identifying potential respiratory health issues.

## Conclusion
The model demonstrated satisfactory accuracy in predicting lung capacity, with metrics like R-squared and RMSE supporting the model's reliability. Visual analyses of error distribution and prediction accuracy validate its practical applications.

## Project Workflow
1. **Data Preprocessing**  
   - Handled missing values and label-encoded categorical columns.
  
2. **Train-Test Split**  
   - Divided the dataset into training (75%) and testing (25%) sets.

3. **Model Training**  
   - Trained a Linear Regression model on the training data.

4. **Evaluation**  
   - Calculated metrics: R-squared, adjusted R-squared, Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).

5. **Visualization**  
   - Displayed error distribution and a joint plot for predicted vs. actual lung capacities.

## Results
- **R-squared**: 0.8487666244239775
- **Adjusted R-squared**:0.847358492435374 
- **RMSE**: 1.0017725292261255
- **MAPE**: 12.403444691147918

## Dependencies
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run
1. Clone the repository.
2. Install required dependencies.
3. Run `LungCap_prediction.py` to train the model and see predictions.

## Future Work
Potential improvements could include testing other regression models, adding feature engineering steps, and exploring more advanced evaluation metrics.
