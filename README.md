# Stock Price Prediction using LSTM

This repository contains a Jupyter Notebook that builds an LSTM neural network to predict stock closing prices using historical data.

---

## 📈 Project Overview

The notebook:
- Downloads historical stock data from Yahoo Finance.
- Visualizes closing price trends.
- Prepares time series data for training an LSTM.
- Trains an LSTM model to predict the next day’s closing price.
- Compares predicted vs actual prices visually.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - yfinance
  - scikit-learn
  - keras (TensorFlow backend)

---

## ⚙️ How to Run

1. **Clone the repository**
    ```bash
    git clone https://github.com/Ammarkarimi/Stock-Market-Prediction.git
    cd Stock-Market-Prediction
    ```

2. **Install requirements**

    You can install required packages using:
    ```bash
    pip install numpy pandas matplotlib yfinance scikit-learn tensorflow
    ```

3. **Run the notebook**
    ```bash
    jupyter notebook
    ```

4. Open `Stock Price Prediction.ipynb` and run all cells.

---

## 📝 Notebook Steps

- **Import Libraries**  
  All necessary Python libraries are imported.

- **Fetch Data from Yahoo Finance**  
  The notebook uses `yfinance` to download historical stock data.

- **Data Visualization**  
  Plots closing prices to show trends.

- **Data Preparation**  
  - Scales data with `MinMaxScaler`.
  - Creates sequences of past 60 days to predict next day’s price.

- **Model Building**  
  LSTM model with:
    - Multiple LSTM layers.
    - Dense output layer.

- **Training**  
  Trained with Mean Squared Error loss.

- **Prediction & Evaluation**  
  - Visual comparison between predicted and actual prices.
  - Calculation of error metrics.

---

## 📊 Example Outputs

Plots include:
- Closing price history
- Loss curve during training
- Predicted vs actual closing prices

---

## ✅ Requirements

- Python ≥ 3.7
- Jupyter Notebook
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - yfinance
  - scikit-learn
  - tensorflow / keras

---

## 💡 Possible Improvements

- Hyperparameter tuning for LSTM layers.
- Incorporate other features (volume, sentiment analysis).
- Test different sequence lengths.
- Deploy as a web app using Flask or Streamlit.

---

## 👤 Author

**Mohammed Ammar Karimi**<br>
💼 [LinkedIn](https://www.linkedin.com/in/mohammed-ammar)<br>
🌐 [Website](https://ammarkarimi.vercel.app/)<br>
📫 [Email](ammarkarimi9898@gmail.com)<br>

