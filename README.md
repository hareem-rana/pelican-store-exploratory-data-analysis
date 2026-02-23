# Pelican Stores – Exploratory Data Analysis

A data analysis project exploring customer purchasing behaviour at Pelican Stores, a division of National Clothing. 
---

## Project Overview

Pelican Stores ran a promotional campaign where discount coupons were distributed to customers of other National Clothing stores. A sample of **100 in-store credit card transactions** was collected during the promotion to help management understand their customer base and evaluate the campaign's effectiveness.

This project performs a full **Exploratory Data Analysis (EDA)** on that dataset, covering descriptive statistics, distributions, and visual insights.

---

## Repository Structure

```
pelican-stores-eda/
│
├── data/
│   └── PelicanStores.xls        
│
├── code/
│   └── pelican_eda.py       
│
├── figures/
│   └── *.png                    
│
├── pelican_analysis.pdf
└── README.md
```

---

## Dataset Variables

| Variable | Description |
|---|---|
| `Customer` | Customer ID |
| `Type of Customer` | Regular or Promotional (used a discount coupon) |
| `Items` | Total number of items purchased |
| `Net Sales` | Total amount charged to credit card ($) |
| `Method of Payment` | Discover, Visa, MasterCard, or Proprietary Card |
| `Gender` | Male or Female |
| `Marital Status` | Married or Single |
| `Age` | Customer age |

> **Promotional customers** used a discount coupon from the campaign. **Regular customers** did not.

---

## Analysis Summary

The report covers:

1. **Descriptive statistics** on Net Sales overall and broken down by customer type (Regular vs Promotional)
2. **Frequency distributions** for categorical variables — payment method, gender, marital status
3. **Cross-tabulations** exploring relationships between customer type and other variables
4. **Data visualisations** including histograms, bar charts, and box plots

---

## Tools & Libraries

- `Python 3.x`
- `pandas` 
- `matplotlib`
- `seaborn` 
- `scipy`
- `numpy`


## Notes

- Dataset contains 100 observations collected over a single trading day during the promotion.
- Analysis completed as part of a university assignment on descriptive statistics and EDA.

