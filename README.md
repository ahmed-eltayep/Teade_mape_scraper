# TradeMap Web Scraper

## Description
This project is a web scraper designed to extract trade data from the TradeMap website using Python. The scraper automates the data collection process, making it easier to analyze trade statistics efficiently.

## Features
- Extracts trade data from TradeMap.
- Handles pagination and dynamic content loading.
- Saves data in CSV format for easy analysis.
- Uses Playwright for efficient web automation.

## Requirements
Ensure you have the following installed before running the scraper:

- Python 3.x
- Playwright
- Pandas

Install dependencies using:
```bash
pip install playwright pandas
playwright install
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/trademap-scraper.git
   ```
2. Navigate to the project directory:
   ```bash
   cd trademap-scraper
   ```
3. Run the scraper:
   ```bash
   python scraper.py
   ```

## Output
The extracted data will be saved as `trade_data.csv` in the project directory.

## Notes
- Ensure your IP is not blocked by TradeMap due to excessive requests.
- You may need to adjust the script if TradeMap updates its website structure.

## License
This project is licensed under the MIT License.

