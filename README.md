# 🌿 Brazil Forest Fires Analysis 🔥

---

## 📚 Project Overview

This project explores data on forest fires in Brazil, focusing on the year 2015. The goal is to understand when and where fires are most common, identify patterns, and offer insights that could help in preventing future fires.

The data includes fire reports from different Brazilian states, recorded by date and month, with the number of fires reported in each entry.

---

## 📊 Dataset Summary

- **Source:** Kaggle - Forest Fires in Brazil  
- **Entries:** 6,454 rows (6,422 after removing duplicates)  
- **Columns:**
  - `year` (int): Year of the record
  - `state` (str): Brazilian state name
  - `month` (str): Month (translated to English)
  - `number` (float): Number of fires reported
  - `date` (str): Date of the record

---

## 🔍 Key Findings

- 📅 **Fire activity peaked during the dry season months**, with July through October consistently showing the highest number of reported incidents across multiple years.
- 🔥 The months with the highest number of fires in 2015 were:
  - January — 4,635 fires
  - October — 4,499 fires
  - July — 4,364 fires
  - August — 4,363 fires
  - December — 4,088 fires  

  This shows fires peak during both the dry season start (January) and later months, possibly related to agricultural burning.
- 🌎 The top 5 states with the most fires on average were:
  1. São Paulo
  2. Mato Grosso
  3. Bahia
  4. Piauí
  5. Goiás
- 📊 In Amazonas, fires were most commonly reported on **Tuesdays, Thursdays, and Fridays**, suggesting human activity on these days might be a factor.
- 🔽 Interestingly, 2015 saw the lowest overall number of fires in Amazonas compared to other years in the dataset.

---

## 🌱 Insights & Suggestions for Fire Prevention

- **Understanding seasonal trends** helps local authorities prepare better for peak fire periods, especially around January and October.
- The pattern of fires on specific weekdays could point to human activities like farming or land clearing, which can be addressed with better awareness campaigns.
- **Community engagement** and education about safe agricultural practices can reduce accidental fires.
- Implementing **controlled burns** and better forest monitoring technologies can help manage and prevent large-scale fires.
- Investing in **early detection systems**, including satellite monitoring, helps catch fires early before they spread.

---

## 🚀 How to Use This Project

### Prerequisites

- Python 3.7 or higher  
- Jupyter Notebook or any Python IDE  
- Libraries: pandas, seaborn, matplotlib  

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/zackahbl1/Brazil-Forest-Fires-EDA.git
    cd Brazil-Forest-Fires-EDA
    ```

2. Install required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Launch the Jupyter notebook to explore the analysis:

    ```bash
    jupyter notebook "Forest Fires In Brazil Project.ipynb"
    ```

---

## 🛠 Tools & Technologies Used

- Python & Pandas for data cleaning and analysis  
- Seaborn & Matplotlib for visualization  
- Jupyter Notebook for interactive exploration  

---

## 🤝 Contributing

Feel free to contribute by opening issues or submitting pull requests! Suggestions on analysis or visualization improvements are welcome.

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🙏 Acknowledgments

Thanks to Kaggle for the dataset and to all contributors who help improve this project.
