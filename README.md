# 📊 Personal Finance Tracker v1.0

**The Original Version - Basic Expense Tracker**

> ⬆️ **See the upgraded version:** [v2.0 with AI insights, modern UI, and advanced features](https://github.com/Shanky085/personal-finance-tracker)

---

## 🔗 Live Demos

- **v1.0 (This Version):** https://finance-tracker-v1-ewsvdakdfpzlvjotnnsqpn.streamlit.app
- **v2.0 (Latest):** https://personal-finance-tracker-hvurvtpaixefbvmzkzy2sx.streamlit.app
---

## Features (v1.0)

- ✅ Basic expense tracking
- ✅ Category-wise breakdown
- ✅ Simple data visualization
- ✅ CSV data storage
- ✅ Transaction history

## Tech Stack

- Python
- Streamlit
- Pandas
- Matplotlib

---

## What Changed in v2.0?

| Feature | v1.0 (This) | [v2.0](https://github.com/Shanky085/personal-finance-tracker) |
|---------|:-----------:|:------:|
| Expense Tracking | ✅ | ✅ |
| Income Tracking | ❌ | ✅ |
| AI Financial Advisor | ❌ | ✅ |
| Budget Alerts | ❌ | ✅ |
| Interactive Charts (Plotly) | ❌ | ✅ |
| Glassmorphism UI | ❌ | ✅ |
| PDF Import | ❌ | ✅ |
| Advanced Filters | ❌ | ✅ |

See [Full Changelog](https://github.com/Shanky085/personal-finance-tracker/releases)

---

*This version is preserved for portfolio demonstration purposes to show project progression.*

<div align="center">

# 💰 Personal Finance Tracker

**Track your daily expenses smartly — visualize, analyze, and stay in control.**

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)

</div>

---

## 🌟 Features

- ➕ **Add /  ️ Delete Expenses** — Log and manage expenses by date, category, amount & description
-   **Pie Chart &   Bar Graph** — Category-wise breakdown and monthly spending trends
- 💳 **Paytm PDF Import** — Auto-import transactions from Paytm UPI statement PDFs
- 📌 **Summary Dashboard** — Total spent, transaction count, highest expense & top category

---

## ⚡ Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Shanky085/expense-tracker.git
cd expense-tracker

# 2. Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS / Linux

# 3. Install dependencies
pip install streamlit pandas matplotlib pdfplumber

# 4. Run the app
streamlit run app.py
```

App opens at **`http://localhost:8501`** 🚀

---

## 🚀 Usage

| Action | How |
|---|---|
| **Add Expense** | Fill in date, category, amount & description → click *"Add Expense"* |
| **Delete Expense** | Select an entry from the dropdown → click *"Delete Expense"* |
| **View Charts** | Scroll down to see pie chart & monthly bar graph |
| **Import Paytm PDF** | Upload your Paytm UPI statement → preview → click *"Import All"* |

---

## 📂 Project Structure

```
expense-tracker/
├── app.py            # Main Streamlit application
├── expenses.csv      # Expense data (auto-generated)
└── README.md         # Documentation
```

---

## 🤝 Contributing

1. **Fork** → **Branch** (`git checkout -b feature/your-feature`) → **Commit** → **Push** → **PR**

**Ideas:** expense editing, PDF reports, budget alerts, multi-currency support, dark mode

---

<div align="center">

**Made with ❤️ using Python & Streamlit** · ⭐ *Star this repo if you found it useful!*

</div>
