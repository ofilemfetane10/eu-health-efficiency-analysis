# 🇪🇺 EU Health Efficiency Analysis

## Project Overview
This project analyzes European healthcare system performance by exploring the relationship between **life expectancy** and **hospital bed infrastructure** using official **Eurostat data**.

Instead of assuming that more healthcare infrastructure automatically leads to better outcomes, this analysis investigates **system efficiency** — identifying countries achieving high life expectancy with fewer physical resources.

---

##  Key Research Question
> Do countries with more hospital beds actually have higher life expectancy?

---

##  Key Findings
- Slight **negative correlation** between hospital beds and life expectancy  
- Many countries achieve **high life expectancy with lower bed capacity**
- Suggests **efficiency, prevention, and care quality** may matter more than raw infrastructure

---

## Why This Matters
Healthcare policy often focuses on expanding infrastructure.  
This project suggests that:
- Preventive care
- Primary care access
- System organization
- Public health investment

may be more impactful than hospital expansion alone.

---

## Dataset Sources
Data pulled from **Eurostat Public APIs**:

- Life Expectancy at Birth
- Hospital Beds per 100,000 Population

---

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn (optional if used)
- Google Colab / Jupyter Notebook

---

##  Analysis Components
###  Life Expectancy Rankings
Country-level comparison of life expectancy.

### Hospital Bed Distribution
Infrastructure availability across Europe.

### Correlation Analysis
Statistical relationship between beds and life expectancy.

### Efficiency Analysis 
Identifies countries achieving:
- High life expectancy  
- Lower infrastructure dependency  

### Category Heatmap
Breakdown of countries by:
- Low / Medium / High Life Expectancy
- Low / Medium / High Bed Capacity

---

## How to Run This Project

### Option 1 — Google Colab (Recommended)
1. Download notebook
2. Upload to Google Colab
3. Run all cells

---

### Option 2 — Local Setup

#### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn requests

Run Notebook
jupyter notebook

Author

Ofile Seneo Mfetane


