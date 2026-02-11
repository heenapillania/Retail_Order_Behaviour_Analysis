# Retail Order Behaviour Analysis: Exploratory Insights & Business Recommendations

This project focuses on analyzing retail order behaviour data to uncover patterns in revenue, customer behavior, and product performance.  
The objective is to generate actionable insights that can support business decision-making using Python-based data analysis tools.

---

## 📁 Files in This Repository

### `retail_order_behaviour_analysis.ipynb`
Complete exploratory data analysis of Online Retail dataset.

Key questions addressed:
## Key Questions Addressed

1. How is Order Quantity distributed when treated as a discrete random variable?
   - What does the Probability Mass Function (PMF) tell us about customer purchasing behavior?
   - Which order quantity occurs most frequently?

2. What is the Expected Order Quantity?
   - How does the average order size compare to the most frequent order size?
   - What does this difference indicate about the impact of large but rare orders?

3. What is the probability of observing a large order (Quantity ≥ 10) given that the customer is from the UK?
   - Using conditional probability:
     P(Large Order | UK)

4. Does customer location (UK vs Non-UK) have a statistically significant relationship with order size?
   - Using a Chi-Square Test of Independence:
     - H₀: Country and Order Size are independent
     - H₁: Country and Order Size are dependent

5. How does transaction volume differ between UK and Non-UK customers?
   - (Countplot: Number of Transactions vs Country Group)

6. How does average revenue compare between UK and Non-UK customers?
   - (Barplot: Country Group vs Average Revenue)

7. What percentage of total revenue comes from UK vs Non-UK customers?
   - (Pie Chart: Revenue Contribution by Country Group)


Tools used: `pandas`, `matplotlib`, `seaborn`

---

## 📊 Key Insights

- Most transactions involve a single item, but large orders increase the expected quantity.
- Large orders are relatively rare in the UK market.
- Chi-square test indicates a statistically significant association between country and order size.
- UK customers contribute a substantial portion of total revenue.


---

## 🛠 Skills & Tools Used

- Python (pandas, matplotlib, seaborn)
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- Jupyter Notebook

---

## 📌 Project Highlights

- Structured data cleaning and preprocessing workflow
- Clear visualizations to support insights
- Focus on business-oriented interpretation of data
- Suitable for internship and entry-level data analyst roles

---

## ▶️ How to Run This Project

1. Clone the repository  
2. Download the dataset from Kaggle (https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)  
3. Open `retail_order_behaviour_analysis.ipynb` in Jupyter Notebook or VS Code  
4. Run the cells sequentially to reproduce the analysis and visualizations  

---

## 📬 Author

**HEENA PILLANIA**  
Aspiring Data Analyst | MSc Mathematics (IIT Hyderabad)  
[LinkedIn](https://www.linkedin.com/in/heenapillania)  
Email: heenapillania82@gmail.com
