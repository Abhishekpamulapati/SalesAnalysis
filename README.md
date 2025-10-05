# 🛍️ Sales Analysis Project

## 📊 Overview
This project analyzes monthly sales data from a fictional electronics store to uncover trends, optimize performance, and visualize insights. Using Python and Pandas, we clean and transform raw CSV files, then apply exploratory data analysis (EDA) to answer key business questions.

---

## 🧰 Tech Stack
- **Python 3.13** (via `.venv`)
- **Jupyter Notebook** (VS Code)
- **Pandas** for data manipulation
- **Matplotlib** for visualization
- **NumPy** for numerical operations

---

## 📁 Project Structure

SalesAnalysis/
├── Sales_Data/                # Raw monthly sales CSV files
├── Analysis.ipynb            # Main notebook with step-by-step analysis
├── .venv/                    # Virtual environment
├── README.md                 # Project documentation



---

## 📌 Key Features
- ✅ Merges 12 months of sales data into a single DataFrame
- ✅ Cleans data: handles NaNs, fixes dtypes, and parses dates
- ✅ Extracts new features: Month, City, Hour, Sales
- ✅ Answers business questions like:
  - What was the best month for sales?
  - Which city sold the most products?
  - What time should advertisements be displayed?
  - What products are often sold together?
- ✅ Visualizes results with bar charts, line plots, and histograms

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/sales-analysis.git
cd sales-analysis

3. Set up the virtual environment
```bash
python -m venv .venv


4. Activate the environment
- On Windows:
```bash
.venv\Scripts\activate
- On macOS/Linux:
source .venv/bin/activate


4. Install dependencies
```bash
pip install -r requirements.txt


5. Launch Jupyter Notebook
jupyter notebook



📈 Sample Insights
- April was the highest-grossing month with over $3.7M in sales.
- San Francisco led in total revenue, followed closely by Los Angeles.
- Macbook Pro Laptop and USB-C Charging Cable were frequently bought together.
- Peak order times were around 11 AM and 7 PM, ideal for ad targeting.

🧪 Future Improvements
- Add interactive dashboards with Plotly or Streamlit
- Automate monthly report generation
- Integrate with real-time sales APIs

🙌 Credits
Inspired by real-world data analysis workflows and guided by hands-on exploration
