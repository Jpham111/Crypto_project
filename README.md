
# Cryptocurrency Interactions Dashboard

This project is a simple web application built using Streamlit that fetches and displays current cryptocurrency data from the [CoinGecko API](https://www.coingecko.com/en/api). It allows users to view key metrics for popular cryptocurrencies and visualize price changes over time.

## Features

- **Display Cryptocurrency Data**: Fetches real-time data for the top 20 cryptocurrencies by market cap.
- **Detailed Metrics**: View details such as current price, market cap, total volume, and 24-hour price change for a selected cryptocurrency.
- **Price Visualization**: Generates a sample price trend graph for the selected cryptocurrency (using simulated data for illustration).

## Getting Started

### Prerequisites

- **Python 3.7+**
- Install dependencies:
  ```bash
  pip install streamlit pandas requests matplotlib
  ```

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/crypto-dashboard.git
   cd crypto-dashboard
   ```

2. Run the application:
   ```bash
   streamlit run app.py
   ```

3. Open the Streamlit app in your browser at `http://localhost:8501`.

## Code Overview

- **fetch_crypto_data**: Fetches cryptocurrency data from CoinGecko’s API, including fields like `name`, `current_price`, `market_cap`, `total_volume`, and `price_change_percentage_24h`.
- **main**: The main function sets up the Streamlit app, displaying the cryptocurrency data, user-selectable options, and a simple time-series price chart.

## How to Use

1. Launch the app and view the table with the latest cryptocurrency data.
2. Select a cryptocurrency from the dropdown to view more details and visualize its recent price trend.

## Future Improvements

- Fetch historical data to replace simulated data in the price change graph.
- Add more detailed analysis, such as 7-day or 30-day price trends.
- Include filtering options for additional metrics and visualization.

## License

This project is licensed under the MIT License.

---
