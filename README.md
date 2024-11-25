# Solar Energy Prediction Using GRU and LSTM

This project focuses on predicting solar energy output using GRU and LSTM models. It demonstrates data preprocessing, model training, and evaluation.

## Files
- `solar_energy_prediction.py`: Contains the code for data preprocessing and model training.
- `solar_energy_data.csv`: Sample dataset used for the project.
- `results.png`: Visualization of model performance.

## Steps Included
1. **Data Preprocessing**
   - Loaded and cleaned the solar energy data.
   - Standardized and split the dataset into training and testing sets.
2. **Model Training**
   - Trained GRU and LSTM models using Keras.
   - Applied dropout to reduce overfitting.
3. **Model Evaluation**
   - Evaluated the models on the test set using Mean Squared Error (MSE).

## Results
- The GRU model achieved a test MSE of `0.01057`.
- The LSTM model showed a slightly higher test MSE.

## Requirements
- Python
- TensorFlow/Keras
- NumPy, pandas, Matplotlib, Seaborn

## Running the Project
To execute the script:
```bash
python solar_energy_prediction.py
