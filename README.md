# 📈 Extracting Stock Data Using a Python Library  

A company's stock share is a piece of the company, more precisely:  
**A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation.**  
This entitles the owner of the stock to a proportion of the corporation's **assets and profits** equal to how much stock they own.  
Units of stock are called **"shares."** 📊  

An investor can buy a stock and sell it later. If the stock price increases, the investor **profits** 💰. If it decreases, the investor incurs a **loss** 📉.  
Determining the stock price is complex; it depends on the number of outstanding shares, the size of the company's future profits, and much more.  
People trade stocks throughout the day, and the **stock ticker** 🏷️ is a report of the price of a certain stock, updated continuously during the trading session.  

💡 **Scenario:**  
You are a **data scientist** 👨‍💻 working for a hedge fund. It's your job to detect suspicious stock activity.  
In this lab, you will **extract stock data** using the Python `yfinance` library. It allows us to retrieve stock data in a **pandas DataFrame**.  

---

## 📜 Table of Contents  
💼 **Topics Covered:**  
- 📌 Using `yfinance` to Extract Stock Info  
- 📌 Using `yfinance` to Extract Historical Share Price Data  
- 📌 Using `yfinance` to Extract Historical Dividends Data  
- 📌 Exercise 🏋️  

⏳ **Estimated Time Needed:** **30 minutes**  

---

## 📦 Installing Dependencies  
```bash
!pip install yfinance
!pip install matplotlib
# !pip install pandas==1.3.3
