# NYSE Stock Market Analysis and Predictive Modeling

## Project Overview

This project focuses on analyzing and predicting stock market data from the New York Stock Exchange (NYSE). Using a comprehensive dataset of stock prices and company fundamentals, we perform various analyses and develop predictive models to gain insights into market dynamics and company performance.

## Key Features

1. **Market Entry and Exit Dynamics Analysis**: Identify companies that entered or exited the market during the data collection period.

2. **Stock Split Detection**: Analyze and detect stock splits by comparing raw and adjusted price data.

3. **Correlation Analysis**: Investigate pairwise correlations between top companies' stock prices and identify potential pairs for trading strategies.

4. **Daily Price Movement Distribution**: Visualize and analyze the distribution of daily stock price movements.

5. **Exploratory Data Analysis**: 
   - Distribution of market capitalization
   - Trading volume trends
   - Comparison of net income and earnings per share (EPS)

6. **Predictive Modeling**: 
   - Linear Regression models to predict Earnings Per Share (EPS)
   - Advanced modeling using Random Forest Regressor

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Key Findings

- Identified 34 new company listings and no delistings during the study period.
- Detected approximately 140 stock splits and their ratios.
- Found high correlations between certain company pairs, potentially useful for pairs trading strategies.
- Observed that daily price movements generally follow a normal distribution with some deviations.
- Discovered declining trading volumes for top companies over time.
- Developed predictive models for EPS with varying degrees of success, with Random Forest outperforming Linear Regression.

## Future Work

- Implement more advanced time series analysis techniques.
- Explore additional machine learning models for prediction.
- Incorporate sentiment analysis from news and social media.
- Develop a real-time prediction system using streaming data.

## Getting Started

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in the `notebooks/` directory

## Data Sources

- NYSE stock price data (2010-2016)
- Company fundamentals data

## Contributors

[Your Name]

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
