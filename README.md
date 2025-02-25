Portfolio Management with Machine Learning


📌 Overview

This project utilizes machine learning models to predict stock returns and optimize investment portfolios. It incorporates dividend forecasting and the Black-Litterman model, allowing for the integration of market data with investor-specific views to make more informed investment decisions. The portfolio is structured around equity investments, algorithmic trading, and cash management, with an objective to outperform the S&P 500 benchmark by 3% annually.

🚀 Features and Functionality

📈 Stock Return Prediction

Utilizes Support Vector Regression (SVR), Multiple Linear Regression (MLR), and Extreme Gradient Boosting (XGB) models.

Implements Capital Asset Pricing Model (CAPM) to assess risk-adjusted returns.

Predicts next-year dividends using the Dividend Discount Model (DDM).

📊 Portfolio Optimization

Mean-Variance Optimization (MVO) is applied to maximize returns while managing risk.

The Black-Litterman Model is used for dynamic asset allocation, integrating market equilibrium with investor views.

🤖 Algorithmic Trading

Employs machine learning-based stock price forecasting to identify trading opportunities.

Investment decisions are made based on price prediction models (SVR, MLR, XGB).

💰 Cash Management

Maintains 10-15% cash allocation to provide liquidity and ensure rebalancing flexibility.

📂 Data Integration

Sources: Historical stock prices, dividends, macroeconomic indicators.

Formats: CSV files and structured financial datasets.

🛠️ Technology Stack

Programming Language: Python

Libraries: NumPy, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

Data Storage: CSV format for historical financial data

Visualization: Matplotlib and Seaborn for data analysis

✅ Prerequisites

Ensure you have the following installed:

Python 3.x (minimum version 3.8)

Required libraries:

pip install numpy pandas scikit-learn xgboost matplotlib seaborn

🔧 Installation Instructions

Clone the repository:

git clone https://github.com/ishujaswani/Portfolio_Management_With_Machine_Learning.git
cd Portfolio_Management_With_Machine_Learning

Create a virtual environment (recommended):

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt  #(Ensure a requirements.txt file exists)

📖 Usage Guide

🗂 Data Preparation

Ensure stock price and dividend data are formatted correctly in CSV files.

Preprocess data using provided scripts to remove anomalies and normalize values.

⚙️ Model Execution

Run Portfolio_Management.ipynb in Jupyter Notebook.

Configure model parameters such as risk tolerance and investment horizon.

📊 Output Interpretation

Portfolio allocations based on Mean-Variance Optimization (MVO).

Predicted returns for individual stocks.

Risk-adjusted performance metrics compared to S&P 500.

🔗 API Documentation (if applicable)

API endpoints allow integration with live financial data sources.

Supports GET/POST requests for real-time portfolio analytics.

🤝 Contributing Guidelines

Contributions are welcome! Please follow these guidelines:

Fork the repository.

Create a new branch for your feature or bug fix.

Commit changes with descriptive messages.

Push to your forked repository.

Create a pull request to merge into the main branch.

📜 License Information

This project is licensed under the Creative Commons Zero v1.0 Universal License. See the LICENSE file for details.

📬 Contact/Support Information

For any questions or support, please contact ij2243@columbia.edu.

