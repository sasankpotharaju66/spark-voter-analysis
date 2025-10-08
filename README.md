# 🗳️ Spark Voter Analysis — Mini Project

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://www.python.org/)
[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-3.5-orange?logo=apache-spark)](https://spark.apache.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

This is my **Apache Spark Mini Project** analyzing the *State‑wise Voter Information 2024* dataset.
The project focuses on turnout patterns, gender participation, NOTA votes, EVM rejections, and — most importantly — **Tendered Votes**, a rare but meaningful metric in elections.

---

## 📂 Project Files

* `SASANK.ipynb` → Spark code and complete analysis  
* `Final_Project_Report.pdf` → Final report with observations and insights  
* `State-wise_Voters_Information_2024_10000.csv` → Dataset used  

---

## 🧰 Tech Stack

* 🐍 Python  
* ⚡ Apache Spark  
* 📊 Pandas, Matplotlib, Seaborn  
* 📓 Jupyter Notebook  

---

## 🌟 Project Highlights

* Cleaned, transformed, and analyzed a **10 000‑row state‑wise voter dataset**  
* Visualized **state‑wise turnout**, **gender‑wise participation**, and **NOTA vote trends**  
* Special focus on **Tendered Votes**, a rare but crucial electoral metric  
* Comparative insights on **EVM rejected vs valid votes**  
* Delivered **actionable insights** in a final report for academic and professional reference  

---

## 📊 Analysis Performed

* ✅ Data loading, cleaning & transformation  
* 🏛️ State‑wise voter turnout analysis  
* 👨‍👩 Gender‑wise participation comparison  
* 🟡 NOTA vote trend analysis  
* 🧮 EVM rejected vs valid vote distribution  
* 🧾 **Tendered Votes highlight & national‑level breakdown**  

---

## 📈 Key Insights

* ✅ **Valid votes** dominate (> 98 %) of total votes cast  
* 🟡 **NOTA votes**, though small, reflect voter choice and democratic engagement  
* 👩 Gender turnout is balanced, with some states showing higher female participation  
* ⚡ **EVM rejection** and **Tendered Votes** are minimal, showing strong election process integrity  

---

## 🔸 Special Focus: Tendered Votes

Tendered votes occur when a **real voter casts a special ballot after someone else tries to impersonate them**.  
This is a **key indicator of election security** and trustworthiness.

* Across states, tendered votes are **extremely low (< 0.01 %)**  
* Indicates:  
  * 🛡️ Strong voter ID verification  
  * ✅ Very low impersonation or fraud cases  
  * 📉 High confidence in electoral systems  
* Even in larger states, the **absolute number is tiny**, highlighting the **robustness of the process**

📊 **Chart included:** Top 5 states with highest tendered votes (still negligible compared to total votes)

---

## 🧭 Visualizations

* 📊 State‑wise voter totals (bar chart)  
* 👨‍👩 Male vs Female voters (grouped bar chart)  
* 📈 Turnout % by state (horizontal bar)  
* 🟡 Top 10 states with NOTA votes (bar chart)  
* 🧮 EVM rejected vs valid votes (pie chart)  
* 🔸 Tendered vote distribution (bar chart — highlighted)  
* 🏁 Final national‑level breakdown  

---

## 🪄 How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/your‑username/Spark‑Voter‑Analysis.git
   cd Spark‑Voter‑Analysis
   ```

2. Install dependencies:  
   ```bash
   pip install pandas matplotlib seaborn jupyter findspark 
   ```

3. Run the notebook:  
   ```bash
   jupyter notebook SASANK.ipynb
   ```
