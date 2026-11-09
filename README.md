# Machakos & Regional Rainfall Advisory System (`plp-da-a2-rainfall-advisory`)

**Student Name:** Collins Kiplangat Rotich  
**Cohort:** Data Analytics with Python - PLP Academy  

---

## 📌 Business Problem Summary
A farmer-support NGO operating across five Kenyan counties (**Nairobi, Nakuru, Kisumu, Mombasa, Machakos**) sends SMS advice on optimal planting windows. Raw station data for Machakos contained missing (`N/A`) and empty (`""`) entries. Using core Python string cleaning, specific `ValueError` exception handling, and vectorized NumPy array operations, this project cleans the dataset, calculates annual and monthly rainfall metrics, identifies wettest months and dry-month counts, determines 2-month peak planting windows, and exports a summary CSV report.

---

## 🚀 How to Run

### Option 1: Run via Google Colab
Click the badge below to execute the analysis notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/collinskiplangatrotich/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/collinskiplangatrotich/plp-da-a2-rainfall-advisory.git
   cd plp-da-a2-rainfall-advisory
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook rainfall_analysis.ipynb
   ```

---

## 🌾 Planting Advisory Summary

* **Optimize Season Launch:** Farmers in Kisumu, Nairobi, and Nakuru should align main crop planting with the April–May long rains, whereas coastal Mombasa farmers should target May–June when combined 2-month rainfall peaks at 350 mm.
* **Manage Dry Season Risks:** Nakuru and Nairobi experience 4 to 5 dry months (< 50 mm/month) annually, necessitating soil moisture conservation, water harvesting, and drought-tolerant crop selection during July–September.
* **Data Quality Caution:** Machakos advisories carry moderate confidence due to imputed values in April (68 mm) and September (68 mm), requiring validation against secondary station telemetry before deploying financial inputs.
