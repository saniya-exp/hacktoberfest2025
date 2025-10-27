# 💸 Currency Converter

A beginner-friendly **Python project** that converts currencies with multiple transactions, conversion history, and total conversions.

---

## 🧩 Features
- Convert any currency to any other currency  
- Built-in exchange rates for popular currencies (USD, INR, EUR, GBP, JPY)  
- For other currencies, program asks you to **enter your own rate**  
- Keeps conversion history  
- Shows total number of conversions  
- Allows you to clear history anytime  
- Simple, interactive terminal interface  

---

## 💱 How It Works

- The converter includes pre-filled exchange rates for:
  - USD ↔ INR, EUR, GBP, JPY  
  - INR ↔ USD, EUR, GBP, JPY  
  - EUR ↔ USD, INR, GBP, JPY  

- If you enter a currency that isn’t in the list (for example, AUD, CAD, or AED),  
  the program will ask you to manually provide the exchange rate.  

  **Example:**
  ```
  Enter source currency code (e.g., USD, INR, EUR): USD  
  Enter target currency code (e.g., USD, INR, EUR): AUD  
  Enter exchange rate (AUD per 1 USD): 1.52  
  ```
  Then it uses that rate for your conversion.

---

## 🔧 Requirements
- Python 3.x  
- Optional: `colorama` library for colorful terminal output  

To install `colorama`:
```bash
pip install colorama
```

---

## 💻 How to Run
```bash
# 1. Open terminal in the project folder
# 2. Run the program
python main.py
```

Then follow the prompts:
1. Enter your name  
2. Choose from the menu:  
   - Convert currency  
   - Show conversion history  
   - Clear history  
   - Exit  

---
