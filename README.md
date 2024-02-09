I build this simple package to  employ my learnings from the Quantitative Risk Management class and get more familiar with Python. 

In this project, I analyze the stock performance of Apple Inc. (AAPL) using historical stock price data, evaluating various financial metrics, visualizations, and statistical calculations to provide a comprehensive assessment of Apple's stock performance.

Prerequisites:
      - Python 3.x
      - Pandas
      - NumPy
      - Matplotlib
      - yfinance
      - Scipy

Installation: Install the required libraries using pip and download the source code from this repository.
      
      # pip install pandas numpy matplotlib yfinance scipy

Usage: Run the Python script stock_analysis.py to execute the analysis and observe the output and the generated plots.
      
      # python stock_analysis.py

Code Structure: The script downloads the stock price data for Apple Inc. using the yfinance library.
      It calculates daily returns and volatility.
      It computes daily moving averages.
      It plots the stock price, moving averages, and volatility.
      It calculates financial assessment metrics such as total return, compounded annual return, standard error of the        mean, Sharpe ratio, maximum drawdown, and annualized volatility.

Output: The script displays financial assessment metrics in the console. It also generates plots that display the stock price, moving averages, and volatility.

Contributing: Contributions are welcome! If you have any suggestions or improvements, please submit a pull request.

License: This project is licensed under the MIT License. T

Acknowledgements: yfinance library for downloading the stock price data. Pandas, NumPy, Matplotlib, Scipy libraries for data manipulation and analysis.

Feel free to customize further based on your preferences and project specifics.
