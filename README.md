# Analyzing Worldwide Immigration Impacts on Economy and Cost of Living 🌍📊

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Major Steps Followed](#major-steps-followed)
- [Insights and Findings](#insights-and-findings)
- [Conclusion and Further Scope](#conclusion-and-further-scope)

---

### Project Overview
This study explores the relationships between **economic indicators** (GDP, unemployment, remittances, income/spending) and the **cost of living** as a strategy to improve understanding of global socioeconomic trends.  
It evaluates how immigration patterns affect economies and lifestyles across nations, using advanced data analysis and visualization.  

Key objective: To reveal how economic stability, living costs, and immigration interplay in shaping global development.

![end_to_end_project](https://github.com/user-attachments/assets/835f8393-6988-4c85-a5e0-8882e7c3306c)

---

### Data Source
Datasets were taken from **Kaggle**:
1. Worldwide Immigration Dataset (JSON)  
2. Worldwide Economic Indicators Dataset (JSON)  
3. Worldwide Cost of Living & Income Dataset (CSV)

---

### Major Steps Followed
1. Fetching unstructured datasets (JSON/CSV) from Kaggle  
2. Storing JSON datasets in **MongoDB**  
3. Storing structured CSV dataset in **PostgreSQL**  
4. Data cleaning, preprocessing, and transformation in Python (Pandas, NumPy)  
5. Outlier detection using boxplots  
6. Exploratory Data Analysis (EDA)  
7. Merging all three datasets on **country** and **year**  
8. Exporting combined dataset into CSV  
9. Loading CSV into **PowerBI** for visualizations  
10. Building an interactive **PowerBI dashboard**  

![apdv_project_steps](https://github.com/user-attachments/assets/511bcc30-1efa-4a99-8fd8-6421d0a62379)

---

### Insights and Findings
1. **Immigration Trends (1990–2020):**  
   Immigration grew steadily, with an acceleration after 2000, showing how nations with stronger economies attract more migrants.  
   ![immigration plots](https://github.com/user-attachments/assets/b7f43e9d-9a78-462f-a454-ddf149084df8)

2. **Top 10 Countries by Immigration:**  
   The US remains the leader, followed by Germany and Russia.  
   ![top 10 countries](https://github.com/user-attachments/assets/bfe8a76f-5160-49f6-b78b-2c460f663f17)

3. **Remittance Dependence:**  
   In countries such as Lesotho, migrant remittances account for 80%+ of GDP, showing heavy reliance on foreign income.  
   ![remittances plot](https://github.com/user-attachments/assets/460058cb-014f-4a93-a7aa-7cb95c56a727)

4. **Cumulative Dashboard:**  
   Key economic indicators: GDP ($198K), GDP growth rate (2.30%), average cost of living ($4.12K), and average immigrants (7.59K).  
   ![APDV Final Dashboard](https://github.com/user-attachments/assets/018f617b-7cc0-410e-84a9-65d384741a1e)

---

### Conclusion and Further Scope
- **GDP:** Year-on-year fluctuations, with major drops during global crises (2008, 2020).  
- **Regional Trends:** North America shows the highest educational costs, while Africa remains the lowest.  
- **Immigration & Economy:** Immigration drives GDP growth and remittance flows, though remittances form just 0.67% of GDP.  
- **Policy Impact:** Results stress the need for balanced policies to manage economic growth, contain rising costs, and reduce regional inequalities.  

This project provides a foundation for **evidence-based policymaking** on global economic stability and improved standards of living.

---

👩‍💻 **Contributors**: Priya Sethi Khurana
🎓 MSc Data Analytics, National College of Ireland (2024–25)  
