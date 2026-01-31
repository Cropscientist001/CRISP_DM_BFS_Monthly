# U.S. Business Formation Trends (2004–2025)

## 📌 Project Motivation
This project explores how entrepreneurship in the United States has shifted over the last two decades. By analyzing **U.S. Census Bureau** data, the goal is to identify regions with the most significant growth and visualize how the volume of business applications has evolved over time.

---

## ⚙️ CRISP-DM Process
To ensure a structured data science approach, this project follows the **CRISP-DM** methodology:

* **Business Understanding**: Defining key questions regarding national and state-level business trends.
* **Data Understanding**: Loading and inspecting monthly statistics sourced from census.gov.
* **Data Preparation**: Cleaning data, handling missing values, and transforming (melting) columns into a time-series format.
* **Modeling/Analysis**: Aggregating data by state and series type to find averages.
* **Evaluation/Visualization**: Creating clear, PEP8-compliant visualizations to communicate insights.
* **Deployment**: Sharing findings via this GitHub repository and a stakeholder-focused blog post.



---

## 📁 File Descriptions
* **`BFS_Analysis.ipynb`**: The primary Jupyter Notebook containing the executable Python code, detailed documentation, and visualizations.
* **`data/bfs_monthly.csv`**: The raw monthly business formation dataset.
* **`requirements.txt`**: A list of Python libraries needed to replicate the environment.

---

## 🛠 Technologies Used
* **Python 3.x**
* **Pandas**: For data manipulation, cleaning, and handling missing values.
* **Matplotlib & Seaborn**: For generating professional data visualizations.

---

## 📈 Key Results
1.  **National Trends**: The analysis identified a significant surge in business applications starting in 2020.
2.  **Top States**: Certain states, notably Florida and California, consistently lead the nation in average monthly business formations.
3.  **Data Integrity**: Successfully addressed missing values and utilized seasonally adjusted data to ensure analysis accuracy.

---

## 📝 Acknowledgements
* Data provided by the [U.S. Census Bureau](https://www.census.gov/).
* Inspiration and coding references from **StackOverflow** and **Kaggle**, used in accordance with project rubric guidelines.
