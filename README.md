# 🏏 Cricket Match Dashboard

An **interactive cricket match dashboard** built with **Streamlit** that displays live/recent cricket match summaries. The app allows users to filter matches by **date, venue, series, and match format** and view detailed match outcomes.

---

## 🚀 Features

* 📅 **Date Filter** – Select matches within a custom range.
* 🏟️ **Venue & Series Filters** – Explore matches by ground and tournament.
* 🏏 **Match Format Filter** – Choose ODI, T20, or Test.
* 📊 **Match Summary Display** – Shows team scores, wickets, and match results.
* 🎨 **Custom Dark-Themed UI** – Modern, clean interface using Streamlit.

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – interactive UI & dashboard
* **Pandas** – data transformation & handling
* **Matplotlib** (optional for charts)
* **Cricbuzz API / JSON Data Source**

---

## 🔄 Data Transformation (ETL Process)

1. **Extract** – Fetch cricket match data from API in **JSON format**. By help of ChatGpt
2. **Transform** –
   * Normalize nested JSON to a **tabular DataFrame**.
   * Convert data types (e.g., `date` → datetime, `score` → integer).
   * Handle missing/no-result matches.
3. **Load** – Pass the cleaned DataFrame into **Streamlit components** for display with filters.

---

## 📖 Example Output

For the match **India vs UAE, T20, Dubai International Stadium:**

* **UAE**: `57/10`
* **INDIA**: `60/1`
* **Result**: ✅ India won by 9 wickets

---

## 💡 My Experience / Learning Outcomes

* Learned to **fetch real-time sports data via APIs**.
* Improved skills in **data wrangling (JSON → DataFrame)**.
* Practiced **ETL concepts** (Extract → Transform → Load).
* Designed an **interactive dashboard** similar to business use cases.
* Strengthened knowledge in **Python, Pandas, Streamlit, and API integration**.

---

## ▶️ How to Run

```bash

# Run the Streamlit app

streamlit run file name.py

```

## 📌 Future Improvements

* Add **player-level analytics (top scorers, bowlers, strike rates)**.
* Include **charts (bar, line, pie) for runs, wickets, partnerships**.
* Connect with a **database** for storing historical data.
* Deploy the app on **Streamlit Cloud / Render / Heroku**.



