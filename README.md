# JPMorgan Chase SWE Virtual Experience – Task 1  
**Interface with a Stock Price Data Feed**

---

## 📋 Project Overview  
This project is part of the JPMorgan Chase & Co. Software Engineering Virtual Experience, completed via the platform The Forage.  
The goal of Task 1 is to set up your development environment, interface with a live stock price data feed (or mock thereof), and implement functionality to support trading analytics.

---

## ✅ Objectives & Learning Outcomes  
- Fork and clone the starter repository.  
- Configure your local development environment (Python, virtual environment, dependencies).  
- Process bid and ask price data for stocks and compute values such as “price” and “ratio”.  
- Create functions/tests that validate your solution against the specification.  
- Gain experience with version control (Git), collaborative workflows, and code documentation.

---

## 🛠 Getting Started  

### Prerequisites  
- Python 3.x (recommended latest version)  
- Git for version control  
- Terminal or command‑line interface  

### Installation & Setup  
1. Clone this repository
```bash
git clone https://github.com/KayBee1880/forage‑JPMC‑SWE‑task‑1.git
cd forage‑JPMC‑SWE‑task‑1
```
2. Create & activate a virtual environment (Linux/macOS example)
```bash
python3 ‑m venv venv
source venv/bin/activate
```
   On Windows if applicable
```bash
python ‑m venv venv
venv\Scripts\activate
```

3. Install dependencies
```bash
pip install ‑r requirements.txt
```
4. Running & Testing
Run the main module or script
```bash
python main.py  # or the appropriate entry‑point
```
5. Execute test suite
```bash
python ‑m unittest discover
```
---

## 📂 Repository Structure
```bash
forage‑JPMC‑SWE‑task‑1/
├── client3.py
├── server3.py
├── client_test.py
├── requirements.txt
├── test.csv
└── README.md
(Modify as needed if your structure differs.)
```
## 📘 Functionality Sample
python
```bash
# Example usage
name, bid_price, ask_price, price = getDataPoint(stock_data)
ratio       = getRatio(priceA, priceB)
print(f"Stock: {name}, Price: {price}, Ratio: {ratio:.2f}")
Expected output:

yaml
Stock: XYZ, Price: 120.50, Ratio: 0.87
(Adjust values according to your data feed and logic.)
```
---

## 📌 Key Features
Data‑feed parsing and validation

Computation of stock price and ratio values

Unit tests demonstrating functionality and edge‑cases

Clear documentation of logic and code flow

---
## 🎯 Future Extensions
Extend to multiple stock symbols or real‑time streaming feed

Add command‑line interface or web dashboard

Integrate visualizations of price and ratio trends

Expand automated test coverage with edge‑cases

---

## 🤝 Contributing
Contributions and improvements are welcome! If you fork this repo, feel free to open a pull request or issue to discuss potential changes.

---

## 📄 License
This repository is intended for educational and demonstration purposes.

---

## 🙌 Acknowledgements
Thank you to the Forage platform and JPMorgan Chase for providing this virtual experience. Learning by doing is key — thanks to the open‑source community for making this possible.
