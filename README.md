# Cotton Price Prediction Using Time Series Models

## Overview

In the realm of agricultural economics, predicting cotton prices holds significant importance for stakeholders ranging from farmers and traders to policymakers and the textile industry. This project undertakes a comprehensive study into predicting cotton prices utilizing various time series models, including ARIMA, VAR, and LSTM. The analysis focuses on two specific markets, offering valuable insights for decision-makers within the cotton industry.

## Models Explored

### ARIMA (Autoregressive Integrated Moving Average)
- A classical time series method known for its simplicity and interpretability.
- Balances model fit and complexity, making it a solid choice for accurate predictions.
- Provides insights into the temporal patterns of cotton prices.

### VAR (Vector Autoregression)
- Considers the interdependencies among multiple time series variables, offering a different approach to modeling.
- Valuable for understanding and predicting the joint behavior of interconnected variables.
- Offers insights into the relationships between cotton prices and other relevant factors.

### LSTM (Long Short-Term Memory)
- A deep learning neural network type known for its ability to capture complex patterns and nonlinear dependencies within data.
- Achieves exceptional predictive accuracy with low Root Mean Squared Error (RMSE).
- Ideal for stakeholders prioritizing predictive precision and accuracy.

## Results and Insights

- **ARIMA**: Strikes a balance between model simplicity and performance, boasting low Akaike's Information Criterion (AIC) and Schwarz Bayesian Information Criterion (BIC) values.
- **VAR**: Offers insights into the interdependencies among variables, although with slightly higher RMSE compared to other models.
- **LSTM**: Stands out as a top performer, achieving exceptional predictive accuracy with impressively low RMSE.
  
## Conclusion

The choice of model depends on the specific needs of the analysis:
- Stakeholders prioritizing predictive accuracy may opt for LSTM.
- Those seeking a balance between accuracy and interpretability may choose ARIMA.
- For understanding and managing volatility in cotton prices, VAR provides valuable insights into interdependencies among variables.

## Usage

1. **Data Collection**:
   - Gather historical cotton price data from reliable sources.
   
2. **Model Training**:
   - Utilize the provided Python scripts to train ARIMA, VAR, and LSTM models on the historical data.
   - Tune model hyperparameters as needed.

3. **Evaluation**:
   - Evaluate model performance using metrics such as RMSE and AIC/BIC values.
   - Choose the model that best suits the specific requirements and objectives.

## File Structure

- `code.ipynb`: Python script for Time Series model's training and predictions.
- `LSTM.py`: Python script for LSTM model training and prediction.
- `README.md`: This file providing an overview and instructions.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Statsmodels (for ARIMA)
- TensorFlow (for LSTM)

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Nishtha Ahuja
- Rachit Patel
- Pradip Patelia
- Dip Patel
- Dhruvi Shah 
