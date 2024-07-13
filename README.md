# Stock Analysis with Monte Carlo Simulation

This project performs stock analysis using historical data from Yahoo Finance and implements a Monte Carlo simulation to predict future stock prices.

## Features

- Download historical stock data from Yahoo Finance
- Perform Monte Carlo simulation to predict future stock prices
- Visualize simulation results with matplotlib

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/stock-analysis-project.git
   cd stock-analysis-project
   ```

2. Install the required libraries:
   ```
   pip install yfinance pandas numpy matplotlib
   ```

## Usage

The project consists of three main parts:

1. Installing necessary libraries
2. Downloading historical data
3. Running Monte Carlo simulation

### 1. Installing Libraries

The project uses `yfinance` for downloading stock data. If not already installed, you can install it using pip.

### 2. Downloading Historical Data

The `download_data` function is used to fetch historical stock data from Yahoo Finance.

### 3. Monte Carlo Simulation

The `monte_carlo_simulation` function performs the simulation and visualizes the results. To run the simulation, you need to specify the stock tickers, date range, number of years to predict, and number of simulations.

## Output

The script generates two plots for each stock:

1. A line plot showing multiple simulated price paths
2. A histogram showing the distribution of final prices

## Customization

You can customize the following parameters:

- `tickers`: List of stock symbols to analyze
- `start_date` and `end_date`: Date range for historical data
- `predict_years`: Number of years to predict into the future
- `num_simulations`: Number of Monte Carlo simulations to run

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This tool is for educational purposes only. Do not use it for actual investment decisions.
