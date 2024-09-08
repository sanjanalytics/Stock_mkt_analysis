# Stock_mkt_analysis

Welcome to the Stock Market Risk-Return Analysis project! In this project, I analyze a selection of major Indian stocks using Python to understand their historical performance in terms of returns and risk. By leveraging the power of Python libraries such as `yfinance`, `pandas`, and `matplotlib`, I explore daily stock price changes, calculate moving averages, daily returns, and create insightful visualizations like histograms and line plots. This project provides a detailed look at the stock market's risk-return profile, focusing on popular stocks like **Reliance**, **Adani Enterprises**, **Sun Pharma**, and **Hindustan Unilever**.

Through this project, the objective is to uncover trends, evaluate stock performance, and understand the risk associated with each stock over a historical period.

## Table of contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Dependencies](#dependencies)

---

## Installation

### To run the Stock Market Risk-Return Analysis project, follow these steps:

1. **Install Anaconda**: Download and install Anaconda from the official website. Anaconda includes Python and Jupyter Notebook, which are essential for running the project.

2. **Python Version**: Ensure you have Python 3.10 or above installed. Verify by running the command `python --version` in the terminal.

3. **Launch Jupyter Notebook**: Open Anaconda Navigator and start Jupyter Notebook. This will open a web browser tab with the Jupyter interface.

## Dataset 

### The Stock Market Risk-Return Analysis project pulls real-time data from Yahoo Finance using the yfinance library. The dataset comprises the adjusted closing prices for major Indian stocks, including:

Reliance Industries
Adani Enterprises
Sun Pharma
Hindustan Unilever
The data is retrieved programmatically using the yfinance API, spanning a customizable time range, typically over the past year. Each stock’s historical data is processed to extract useful information like daily returns and moving averages.

Note: Since the data is fetched dynamically using the yfinance library, no static dataset is provided in the repository.

5. **Package Dependencies**: The project requires the following packages for data analysis and visualization. You can install them using `pip` or `conda`:
   ```bash
   pip install numpy pandas yfinance matplotlib seaborn

## Project Structure

### The Stock Market Risk-Return Analysis project is organized as follows:

Stock_Market_Risk_Return_Analysis.ipynb: This is the main Jupyter Notebook containing the analysis, code explanations, and visualizations that uncover insights from the stock market data.

README.md: This README file provides an overview of the project, instructions for installation, and a guide to running the analysis.

## Usage

### Follow these steps to use the Stock Market Risk-Return Analysis project:

Ensure Installation: Complete the installation steps in the "Installation" section above.

Run the Notebook: Launch Jupyter Notebook, navigate to the project directory, and open Stock_Market_Risk_Return_Analysis.ipynb.

Execute the Cells: Run each code cell sequentially to fetch the stock data, calculate returns, and generate visualizations.

Modify or Experiment: Feel free to modify the stock list or time range to analyze different stocks or periods. Experiment with various statistical techniques and visualization styles to gain additional insights.

Explore Visualizations: The project includes line charts for stock prices, moving averages, and histograms for daily returns. Interact with the graphs to better understand the risk-return profiles of the selected stocks.

## Key Findings

### During the analysis of Indian stock data, several insights and patterns were uncovered. Some notable highlights include:

Stock Performance Trends: By calculating moving averages (10-day, 20-day, 50-day), the project identifies key trends in stock prices, such as upward or downward momentum.

Risk Profile via Daily Returns: The daily return analysis reveals the volatility of each stock, with histograms offering a visual representation of the distribution of returns.

Relative Risk Comparison: A comparative analysis of the daily returns of different stocks highlights which stocks exhibit higher volatility (risk) and which are relatively stable.

These findings provide a deeper understanding of stock performance and the inherent risk in the market, offering a comprehensive view of each stock's return potential over the chosen time period.

## Dependencies

### To run this project, the following Python libraries are required:

numpy: for numerical computations
pandas: for data manipulation and analysis
yfinance: to fetch stock market data from Yahoo Finance
matplotlib: for plotting visualizations
seaborn: for enhanced data visualization

