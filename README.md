# DBVac Capstone Project

## 📘 Overview
This project was created as part of a capstone for my Business Data Analytics program. It presents a full-scale business case for DBVac, a fictional company evaluating the launch of a new vacuum product. The goal was to identify:
1. The most financially viable product to develop and release.
2. The best internal candidates to lead the product's launch.

The project uses a combination of **SQL**, **Excel modeling (Expected Cost & NPV Analysis)**, and **a Balanced Scorecard framework** to deliver a data-driven recommendation for DBVac’s executive team.

---

## 📊 Project Components

### 1. Expected Cost & NPV Analysis
- Built an Excel model to estimate expected R&D costs for three potential products (`Fin`, `Snorkel`, and `Facemask`) using probability-weighted scenarios.
- Calculated Net Present Value (NPV) over 5 years at a 10% discount rate for each product.
- **Result**: The `Facemask` product, while having the highest initial R&D cost, yielded the **highest NPV** at $747,105.

### 2. Product Manager Selection (Balanced Scorecard)
- Queried internal employee data using **SQL**.
- Built a **Balanced Scorecard model** in Excel using six criteria:
  - Trustworthiness
  - Experience
  - Popularity
  - Bonus Score (cost control)
  - “Dust Factor” (relationship with CEO)
  - Softball Game Winner (a proxy for competitiveness)
- Normalized scores using **z-scores**, applied weights based on executive input, and selected the two top-scoring managers:
  - **Evan Thompson** and **Everleigh Young**

### 3. Python Integration *(Optional Appendix)*
- Included a Jupyter Notebook that replicates some score calculations and visualization in Python for portfolio demonstration.

---

## 📁 Files Included
- `Business_Case_Report.docx`: Full written business case summary and recommendations
- `Appendix_A1_EC_Analysis.xlsx`: Expected Cost and NPV calculations
- `Appendix_B1_NPV_Analyses.xlsx`: NPV breakdowns per product
- `Appendix_C2_Balanced_Scorecard_Analysis.xlsx`: Scorecard for product manager evaluation
- `Appendix_C1_Balanced_Scorecard_Queries.docx`: SQL queries for retrieving manager evaluation data
- `Appendix_D1_Capstone_Python_Program.ipynb`: Python program used for additional analysis

---

## 💡 Skills Demonstrated
- Data querying with SQL
- Financial modeling with Excel (Expected Cost, NPV)
- Business decision frameworks (Balanced Scorecard)
- Data normalization and weighting (z-scores)
- Communication of insights in a structured business case
- Optional Python scripting

---

## 🧠 Key Takeaways
Through structured analysis, the Facemask product emerged as the strongest investment option, and a rigorous data-driven scorecard process identified the most capable leaders for the launch. This project reflects my ability to apply analytics to real-world business decisions.
