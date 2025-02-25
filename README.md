# Stock Market Predictor

## Overview
This project is a **Stock Market Predictor** application that allows users to visualize stock data and predict stock prices using a deep learning model. It is built using **Streamlit**, **Keras**, **Yahoo Finance API**, and **Matplotlib**.

## Features
- Fetch historical stock data from Yahoo Finance.
- Visualize stock price trends with **Moving Averages (MA50, MA100, MA200)**.
- Predict future stock prices using a pre-trained deep learning model.
- Interactive web interface using **Streamlit**.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Pip

### Install Required Libraries
Run the following command to install necessary dependencies:
```bash
pip install numpy pandas yfinance keras streamlit scikit-learn matplotlib
```

## Usage
### Running the Application
To start the Streamlit application, use the command:
```bash
streamlit run app.py
```

### How It Works
1. Enter the stock symbol (e.g., `GOOG` for Google, `AAPL` for Apple).
2. The app fetches stock data from Yahoo Finance from **2012 to 2022**.
3. Displays stock prices with **Moving Averages (50, 100, 200 days)**.
4. The pre-trained deep learning model predicts future stock prices.
5. Comparison of **Predicted vs Actual Prices** is plotted for analysis.

## Screenshots
### Stock Price Visualization
![Moving Averages Plot](screenshots/ma_plot.png)

### Prediction vs Original
![Prediction Plot](screenshots/prediction_plot.png)

## Model Details
- The model used for prediction is a **Deep Learning model trained using Keras**.
- It takes the past 100 days' stock prices as input to predict future values.

## Data Source
- **Yahoo Finance API**: Fetches real-time and historical stock market data.
- Visit [Yahoo Finance](https://finance.yahoo.com/) to find stock symbols.

## Repository Structure
```
📂 Stock Market Predictor
 ├── 📜 app.py                # Streamlit app script
 ├── 📜 Stock Predictions Model.keras # Trained deep learning model
 ├── 📜 requirements.txt      # List of dependencies
 ├── 📜 README.md             # Documentation
 ├── 📂 screenshots           # Folder for images/screenshots
```

## Contributing
Feel free to contribute by improving the model or adding new features. Follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-new`).
3. Commit changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-new`).
5. Open a **Pull Request**.

## License
This project is licensed under the **MIT License**.

---
### 🔗 Links
- GitHub Repository: [Your Repo Link Here]
- Streamlit Documentation: [https://streamlit.io/](https://streamlit.io/)

