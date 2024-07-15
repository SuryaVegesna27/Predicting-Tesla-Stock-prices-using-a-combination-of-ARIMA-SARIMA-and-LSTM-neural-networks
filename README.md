### README

## Tesla Stock Price Prediction

### Description
This project aims to predict the opening stock prices of Tesla Inc. using a combination of ARIMA, SARIMA, and LSTM neural network models. By integrating traditional statistical models with cutting-edge deep learning techniques, we strive to enhance the predictive accuracy and reliability of financial market forecasts.

### Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.7** or higher installed
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn**, **Statsmodels**, **TensorFlow/Keras** libraries installed

### Installation and Setup
To install and set up the project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/tesla-stock-prediction.git
   cd tesla-stock-prediction
   ```

2. **Set up the Python Environment:**
   Create a virtual environment and install the required libraries:
   ```sh
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebooks:**
   Open and run `Final_Project.ipynb` in Jupyter.

### Using the Project
Once the Jupyter Notebook is open, you can run the cells to execute the following steps:

1. **Data Collection and Preprocessing:**
   - Download Tesla's stock price data from Yahoo Finance using the `yfinance` module.
   - Handle date conversions and normalize financial indicators using MinMaxScaler.

2. **Exploratory Data Analysis:**
   - Analyze historical trends and volatility in Tesla's stock prices.
   - Conduct statistical diagnostics and apply transformations to achieve stationarity.

3. **Model Development:**
   - **ARIMA Model:** Fit an ARIMA (1,0,1) model based on ACF and PACF analyses.
   - **SARIMA Model:** Extend ARIMA to SARIMA (1,0,1) (1,1,1,5) to capture seasonal effects.
   - **LSTM Model:** Build an LSTM neural network with sequential layers to capture long-term dependencies.

4. **Model Evaluation and Forecasting:**
   - Evaluate models using RMSE, AIC, and BIC metrics.
   - Generate forecasts for Tesla's stock prices and compare model predictions.

### Key Findings
- **ARIMA Model:** Achieved an RMSE of 0.036 on training data and 0.038 on test data, capturing linear trends effectively.
- **SARIMA Model:** Demonstrated improved seasonal capture with an RMSE of 0.0362, indicating a potential rebound in stock prices.
- **LSTM Model:** Successfully learned underlying trends and non-linear relationships with an RMSE of 4.02, closely aligning predictions with actual prices.

### Results Analysis and Interpretation
- **ARIMA and SARIMA:** Provided robustness in trend and seasonal analysis, offering insights into linear and seasonal patterns.
- **LSTM:** Delivered strong performance in modeling non-linear patterns and long-term dependencies, indicating its suitability for complex time-series forecasting.

### Contributing to the Project
To contribute, follow these steps:
1. **Fork the repository.**
2. **Create a branch:**
   ```sh
   git checkout -b <branch_name>
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -m '<commit_message>'
   ```
4. **Push to the original branch:**
   ```sh
   git push origin <project_name>/<location>
   ```
5. **Create a pull request.**

### License
This project is licensed under the @2023 Surya Varma Vegesna.

### Contact
If you have any questions or want to contribute, please email us at surya@example.com.
