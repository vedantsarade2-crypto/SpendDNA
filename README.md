# SpendDNA 💰

> A Python-based transaction analysis project that turns messy bank/UPI transaction data into a simple financial story.

SpendDNA analyzes six months of transaction data and answers questions like:

- Where is most of the money being spent?
- Which vendors receive the most money?
- Which spending categories are increasing or decreasing?
- At what time of day does spending happen?
- Which transactions look unusual?
- What kind of spender is the user?

---

## 📌 Project Overview

SpendDNA is a mini-project focused on transaction data analysis using Python, Pandas, and NumPy.

The project starts with a raw CSV file containing transaction records. The data is cleaned and transformed, vendors are identified from transaction descriptions, spending categories are assigned, and different analytical features are calculated.

The final output is a formatted SpendDNA Report printed directly in the notebook.

### Project Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning
        ↓
Vendor Extraction
        ↓
Category Tagging
        ↓
Spending Overview
        ↓
Monthly Trend Analysis
        ↓
Time-of-Day Analysis
        ↓
Anomaly Detection
        ↓
Spending Archetype Detection
        ↓
Final SpendDNA Report
