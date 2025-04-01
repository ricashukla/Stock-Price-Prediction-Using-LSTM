# Stock Price Prediction Using LSTM

## 📌 Introduction
Stock price prediction is a challenging task due to the highly volatile nature of the market. This project utilizes a **Long Short-Term Memory (LSTM)** model to predict stock prices based on historical data. The model learns patterns in past stock prices and makes future predictions.

## 📂 Dataset
- The dataset consists of historical stock prices, including:
  - **Open**
  - **High**
  - **Low**
  - **Close**
  - **Volume**
- Source: Yahoo Finance / Kaggle (Specify the exact source if applicable)
- Data is preprocessed and normalized before training the LSTM model.

## 📊 Methodology
1. **Data Preprocessing**
   - Load the dataset
   - Handle missing values (if any)
   - Normalize data using MinMaxScaler
   - Create a sliding window of past stock prices
2. **LSTM Model Architecture**
   - Input layer: Takes past stock price sequences
   - LSTM layers with dropout to prevent overfitting
   - Dense layer for final prediction
3. **Model Training & Evaluation**
   - Train the model using a training dataset
   - Validate the model using test data
   - Evaluate using **Mean Absolute Error (MAE)** and **R² Score**
4. **Prediction & Visualization**
   - Predict future stock prices
   - Plot actual vs predicted prices

🛠 Installation
```sh
Clone the repository
git clone https://github.com/your-username/Stock-Price-Prediction-Using-LSTM.git
cd Stock-Price-Prediction-Using-LSTM

Install required dependencies
pip install -r requirements.txt
```

🚀 Usage
```python
# Run the main notebook
jupyter notebook LSTM_model.ipynb
```

🔍 Results
- **Mean Absolute Error (MAE):** 11.31%
- **R² Score:** 0.78
- The model captures the general trend but can be improved further.

📌 Improvements & Next Steps
- Add **technical indicators** (SMA, EMA, RSI, MACD) for better predictions.
- Tune **LSTM hyperparameters** (more layers, Bidirectional LSTM, Dropout adjustment).
- Try **different time window lengths** (30, 60, 90 days) for better trend learning.

📝 License
This project is open-source under the MIT License.

📬 Contact
For questions or contributions, reach out via GitHub Issues or Email.

---
🔗 Connect with Me
[GitHub](https://github.com/ricashukla) 

