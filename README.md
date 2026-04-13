# 📊 Capital Asset Pricing Model (CAPM) Calculator

A simple and interactive **CAPM Calculator Web App** built using **Streamlit**, **Python**, and **Plotly**.
This app helps users analyze stock performance, calculate **Beta (β)**, **Alpha (α)**, and visualize stock trends compared to the market.

---

## 🚀 Features

* 📈 Fetch real-time stock data using Yahoo Finance
* 📊 Interactive charts using Plotly
* 🔄 Normalize stock prices for comparison
* 📉 Calculate daily returns
* 📐 Compute:

  * **Beta (β)** – Market risk
  * **Alpha (α)** – Excess return
* 🧠 CAPM-based analysis for selected stocks
* ⚡ Fast and user-friendly UI with Streamlit

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Pandas**
* **NumPy**
* **yFinance**
* **Plotly**

---

## 📂 Project Structure

```
CAPM/
│── CAPM_Return.py        # Main Streamlit app
│── capm_function.py      # Helper functions (plotting, returns, beta)
│── requirements.txt      # Dependencies (optional)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/capm-calculator.git
cd capm-calculator
```

---

### 2️⃣ Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

👉 OR manually:

```bash
pip install streamlit pandas numpy yfinance plotly
```

---

### 4️⃣ Run the app

```bash
python -m streamlit run CAPM_Return.py
```

---

## 🌐 Output

* Local URL: http://localhost:8501
* Interactive dashboard opens in your browser

---

## 📊 CAPM Formula

The **Capital Asset Pricing Model (CAPM)** is used to calculate expected return:

[
E(R_i) = R_f + \beta_i (R_m - R_f)
]

Where:

* (E(R_i)) = Expected return
* (R_f) = Risk-free rate
* (\beta_i) = Beta of the asset
* (R_m) = Market return

---

## 📸 Screenshots

<img width="1906" height="816" alt="image" src="https://github.com/user-attachments/assets/8a717a19-93f9-4792-bf44-6e06846eb718" />

---

<img width="1913" height="842" alt="image" src="https://github.com/user-attachments/assets/ffddcd7e-915b-48a7-a5b5-914ee42583b8" />

---

<img width="1893" height="577" alt="image" src="https://github.com/user-attachments/assets/f658b723-1718-41e5-b834-eb7ffe4eac77" />

---

## ❗ Notes

* Uses `yfinance` instead of outdated `pandas_datareader`
* Compatible with latest Python versions (3.12+)
* Ensure internet connection for fetching stock data

---

## 🤝 Contributing

Feel free to fork this project and improve it. Contributions are welcome!

---

## 📧 Contact

**Aniket Firke**
💼 Open to Data Analyst / Cloud Engineer (AWS+DevOps) roles

