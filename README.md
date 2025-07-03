# CARBON-EMISSION-PREDICTION

This project focuses on predicting carbon emissions using AI and data science techniques. The workflow includes data cleaning, exploration, preparation, model building, and forecasting.

## Project Structure

- `climate_change_download_0.xls` — Raw dataset containing climate and emission data.
- `data_cleaned.csv` — Cleaned dataset after preprocessing.
- `data-exploration.ipynb` — Jupyter notebook for initial data exploration and visualization.
- `data-preparation.ipynb` — Notebook for data cleaning, feature engineering, and preparation.
- `model-building.ipynb` — Notebook for building and evaluating machine learning models.
- `forecasting_co2_emmision.pkl` — Trained model for CO₂ emission prediction.
- `README.md` — Project documentation.

## Workflow

1. **Data Cleaning:**  
   The raw data from `climate_change_download_0.xls` is cleaned and saved as `data_cleaned.csv` using pandas in the `data-preparation.ipynb` notebook.

2. **Exploration:**  
   Data is explored and visualized in `data-exploration.ipynb` to understand trends, missing values, and feature distributions.

3. **Preparation:**  
   Features are selected and engineered in `data-preparation.ipynb` to prepare the dataset for modeling.

4. **Model Building:**  
   Machine learning models are trained and evaluated in `model-building.ipynb`.
   For model training, the Random Forest Regression algorithm was used. The steps included:

   - Splitting the dataset into training and testing sets
   - Selecting relevant features for prediction
   - Training the Random Forest Regression model on the training data
   - Evaluating the model using metrics such as Mean Squared Error (MSE) and R² score
   - Saving the best model as `forecasting_co2_emmision.pkl`

5. **Prediction:**  
   The trained model can be used to predict future carbon emissions based on input features.

## Components Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- Jupyter Notebook

if any file is not rendering because of its size kindly refer the below drive
model: https://drive.google.com/drive/folders/1-_WImLgMH_KB75NtgukY9P73oVnwNtH6
