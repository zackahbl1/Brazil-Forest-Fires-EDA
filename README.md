# 🌲 Brazil Forest Fires EDA 🔥

**Author:** Zephaniah Ackah-Blay  
**Date:** June 28, 2025  

---

## 📖 Overview

This exploratory data analysis (EDA) project investigates forest fire incidents across Brazilian states from 1998 to 2017. The dataset includes fire counts reported monthly, state-wise, and daily data, offering insights into trends, peak periods, and regional fire activity.

---

## 🗂️ Dataset Details

- Source: [Kaggle - Forest Fires in Brazil](https://www.kaggle.com/datasets/gustavomodelli/forest-fires-in-brazil)
- Entries: 6,454 rows (after removing duplicates: 6,422)
- Columns:
  - `year` (int): Year of the record
  - `state` (object): Brazilian state name
  - `month` (object): Month (translated to English)
  - `number` (float): Number of fires reported
  - `date` (object): Date of the record

---

## 🔍 Key Findings

- 📅 **Year with most records:** 2015 (324 entries)  
- 🔥 **Top months for fires in 2015 (total fires):**  
  1. January — 4,635 fires  
  2. October — 4,499 fires  
  3. July — 4,364 fires  
  4. August — 4,363 fires  
  5. December — 4,088 fires  

- 🌎 **Top 5 states by average fires reported (highest to lowest):**  
  São Paulo, Mato Grosso, Bahia, Piauí, Goiás  

- 📊 **Days of the week with highest fire counts in Amazonas:**  
  Tuesday, Thursday, Friday  

- 🔽 **2015 was the year with the lowest fire count in Amazonas compared to other years.**

---

## 🚀 How to Use This Project

### Prerequisites

- Python 3.7+  
- Jupyter Notebook or any Python IDE  
- Libraries: `pandas`, `seaborn`, `matplotlib`

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/zackahbl1/Brazil-Forest-Fires-EDA.git
