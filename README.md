# 📊 PhonePe Transaction Insights - Google Colab Notebook

This repository contains a **full Google Colab notebook** for analyzing PhonePe transaction data at **state and district levels** in India.

It uses data from the [PhonePe Pulse GitHub repository](https://github.com/PhonePe/pulse) and provides interactive dashboards for easy visualization.

---

## **Features**

- ✅ Aggregates transaction data by **state and district**
- ✅ Shows **top states** by transaction amount
- ✅ Displays **payment type analysis** per state
- ✅ Identifies **top districts** by transaction amount
- ✅ Interactive **dashboard with dropdowns** for Year, Quarter, and State
- ✅ Choropleth **India map visualization** by transaction amounts
- ✅ Saves **processed data to Google Drive** as CSV

---

## **Usage**

1. Open the notebook in **Google Colab**.
2. Run all cells sequentially.
3. Interact with the dropdowns to explore transaction data.
4. Export the analysis to Google Drive if needed.

---

## **Requirements**

- Python 3.x
- Google Colab
- Packages:
  - `pandas`
  - `plotly`
  - `matplotlib`
  - `ipywidgets`
  - `sqlite3` (standard library)

Install missing packages with:

```python
!pip install pandas plotly matplotlib ipywidgets
