# Aerofit Treadmill Case Study – Customer Profiling & Business Insights

## 📌 Overview
Aerofit is a leading fitness equipment brand offering treadmills across three segments:
- **KP281** – Entry-level ($1,500)
- **KP481** – Mid-level ($1,750)
- **KP781** – Advanced ($2,500)

The objective of this case study is to analyze customer characteristics for each treadmill model and provide actionable recommendations for targeted marketing and product positioning.

---

## 📊 Dataset
- **Size:** 180 customers
- **Features:** Product Purchased, Age, Gender, Education, Marital Status, Usage (per week), Income, Fitness (1–5 scale), Miles (per week)
- **Quality:** No missing values

---

## 🔍 Analysis Workflow
1. **Data Import & Exploration** – Load dataset, inspect structure, check missing values & outliers.  
2. **Univariate Analysis** – Explore each feature individually (age distribution, income ranges, fitness scores).  
3. **Bivariate Analysis** – Study relationships between product purchased and customer demographics.  
4. **Probability Analysis** – Construct contingency tables; calculate marginal & conditional probabilities.  
5. **Customer Profiling** – Build profiles for KP281, KP481, and KP781 buyers.  
6. **Business Recommendations** – Translate insights into marketing and sales strategies.

---

## 📈 Key Findings
- **Product Distribution:** KP281 (44%), KP481 (33%), KP781 (22%)  
- **Profiles:**  
  - **KP281:** Young (18–28), lower income, fitness beginners, casual users  
  - **KP481:** Adults (25–35), medium income, balanced gender mix, regular users  
  - **KP781:** Older (30–40), higher income (> $60K), advanced fitness levels, predominantly male  
- **Gender Effect:** Females prefer KP281 (53%), while males are 3× more likely to buy KP781 (32%)  
- **Behavioral Patterns:** Age and income rise together; fitness, usage, and miles are strongly correlated  

---

## 💡 Business Recommendations
- **KP281:** Market to students/young professionals with budget bundles and starter packs.  
- **KP481:** Position as “best value” for families and working adults; bundle accessories (mats, dumbbells).  
- **KP781:** Target premium customers via gyms, wellness clubs, and corporate wellness programs.  
- **Gender Strategy:** Promote KP781 to men; design KP281 starter packages for women.  
- **Upgrade Path:** Introduce trade-in and loyalty programs to move customers up the product ladder.  
- **Cross-Sell:** Offer accessories (shoes, mats, wearables) to increase customer lifetime value.  

---

## 🚀 How to Run
1. Open the Jupyter Notebook or Python script provided in this repository.  
2. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.  
3. Run all cells to reproduce the analysis and visualizations.  
4. Review the final customer profiles and recommendations.  

---

## 📂 Repository Structure
- `README.md` – Project overview and insights  
- `aerofit_analysis.ipynb` – Jupyter Notebook with step-by-step analysis  
- `aerofit_analysis.py` – Python script version of the workflow  
- `data/aerofit_treadmill.csv` – Dataset used for analysis  

---

## ✅ In Short
Aerofit can grow sales by **aligning each treadmill with the right customer segment**, leveraging **gender-based strategies**, and offering **structured upgrade paths** supported by personalized recommendations.
