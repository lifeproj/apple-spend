## About

A Python script that extracts paid transactions from Apple Account HTML pages and generates:

- A CSV file with all transactions (date, item name, amount, subscription status)
- An HTML summary report with charts showing repeated transactions and yearly spending trends

## Usage

1. **Prerequisites**: Install required dependencies:

   ```bash
   pip install beautifulsoup4 matplotlib
   ```

2. **Prepare your data**: Save the HTML page from [reportaproblem.apple.com](https://reportaproblem.apple.com/) as `apple.html` in the project directory.

3. **Run the script**:

   ```bash
   python extract_transactions.py
   ```

4. **Output files**:

   - `apple_transactions.csv` - All transactions in CSV format
   - `apple_transactions_summary.html` - Interactive summary report with charts
