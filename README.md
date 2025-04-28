
# StockMind 📈

StockMind is a Stock peer competitor and Stock Analysis tool that identifies peer competitors for a company and fetches its live stock prices.

---

## 🚀 Features

✅ Competitor Analysis – Uses Gemini LLM to find peer competitors based on the company's industry.  
✅ Real-Time Stock Prices – Fetches live stock data using the yfinance library.  
✅ Automated Ticker Retrieval – Extracts the stock ticker symbol from Alpha Vantage API.  
✅ Company Information Fetching – Uses Wikipedia API to gather company details.  
✅ US Market Focused – Currently designed for United States stock exchanges.

---

## 🔧 Tech Stack

- Python 🐍
- Wikipedia API – Fetches company descriptions
- Gemini LLM – Identifies peer competitors
- Alpha Vantage API – Retrieves stock ticker symbols
- yfinance – Fetches real-time stock prices

---

## 📜 Installation

1️⃣ Clone the repository:

```bash
git clone https://github.com/sharathchandra-patil/StockMind.git
cd StockMind
```

2️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Set up API keys:

- Get an Alpha Vantage API Key from [Alpha Vantage](https://www.alphavantage.co/).
- Store it in an `.env` file or set it in your environment variables:

```bash
ALPHA_VANTAGE_API_KEY=your_api_key
```

---

## 🚀 Usage

Run the script and input a company name:

```bash
python stockmind.py
```

Example Output:

```
Company: Apple Inc. (AAPL)
Industry: Technology
Peer Competitors: Microsoft, Google, Amazon
Current Stock Price: $180.32
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---
## 🙋‍♂️ How to Contribute

We welcome contributions from everyone! 🚀

If you're new to open-source, you can start with our [Good First Issues](https://github.com/sharathchandra-patil/StockMind/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

### 🛠 Steps to Contribute:
1. Fork this repository.
2. Clone your forked repo locally.
3. Create a new branch for your feature or fix.
4. Make your changes.
5. Test your changes locally.
6. Commit your changes with a clear message.
7. Push your branch and open a Pull Request (PR) to the `main` branch.
8. Wait for review and feedback!

### 💬 Contribution Ideas:
- Solve an open [Good First Issue](https://github.com/sharathchandra-patil/StockMind/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
- Fix bugs
- Improve project documentation
- Add new features (Check open [Feature Requests](https://github.com/sharathchandra-patil/StockMind/issues?q=is%3Aissue+label%3Afeature))
- Optimize performance or UI



📢 **Need help?**  
Open a [Discussion](https://github.com/sharathchandra-patil/StockMind/discussions) or raise an Issue! We're happy to assist you.

---

## 🛠️ Contribution Guidelines

- **Fork** this repository and **clone** it to your local machine.
- **Create a new branch** for your feature or bug fix.
- **Write clear, concise commit messages**.
- Ensure your code **follows proper Python coding standards** (use tools like `flake8` if needed).
- Test your code properly before submitting a **Pull Request (PR)**.
- Reference the related **Issue ID** (if applicable) in your PR description.
- Open a Pull Request and fill out the provided template.
- Be respectful in discussions and reviews — constructive feedback helps everyone!

---

## 👨‍💻 Contributors

- Sharathchandra Patil
- Srajan VN
- Srinandan M
- Vikas NR

---

## 📜 License

This project is licensed under the MIT License.
