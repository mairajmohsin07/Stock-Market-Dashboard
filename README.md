# Stock Market Dashboard

A comprehensive stock market dashboard built using Dash, a Python framework for building analytical web applications. The dashboard allows users to visualize stock data, technical indicators, dividends, and market heatmaps for the S&P 500, NASDAQ, and Dow Jones.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Stock Data Visualization:** View candlestick charts with volume bars for selected stocks.
- **Technical Indicators:** Analyze technical indicators such as moving averages, RSI, MACD, ATR, and CCI.
- **Dividends:** Track dividend payments for selected stocks.
- **Market Heatmaps:** Explore market trends using color-coded treemaps for S&P 500, NASDAQ, and Dow Jones.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.
- Required Python packages listed in `requirements.txt`.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/stock-market-dashboard.git
   ```

2. Install the required dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Navigate to the project directory:

   ```bash
   cd stock-market-dashboard
   ```

2. Run the `app.py` file:

   ```bash
   python app.py
   ```

3. Access the dashboard in your web browser at `http://localhost:8050`.

## Configuration

- Customize cache expiration time in `cache_management.py`.
- Adjust API keys and other configurations in respective modules (e.g., `news_feed.py`, `heatmap.py`).

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
