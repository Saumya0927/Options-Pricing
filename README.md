# Black-Scholes Option Pricing Model (black_scholes_live_data.ipynb)

This Python script implements the Black-Scholes model for option pricing and analysis. It provides a comprehensive tool for calculating option prices, Greeks, and visualizing results.

## Features

- Calculates option prices and Greeks (delta, gamma, vega, theta, rho) for both call and put options
- Fetches real-time market data using yfinance
- Estimates implied volatility from historical data
- Analyzes options data for a specified stock and expiration date
- Generates visualizations for option prices and Greeks

## Key Components

- `BlackScholesModel` class: Encapsulates all calculations and data retrieval
- Real-time data fetching: Uses yfinance to get current stock prices and treasury rates
- Greeks calculation: Implements formulas for delta, gamma, vega, theta, and rho
- Data analysis: Compares Black-Scholes valuations with market prices
- Visualization: Plots option prices and Greeks for both call and put options

## Usage

1. Set the desired stock ticker and expiration date in the main block
2. Run the script to see a full analysis including:
   - Model parameters
   - Options analysis for calls and puts
   - Graphical representations of option prices and Greeks
