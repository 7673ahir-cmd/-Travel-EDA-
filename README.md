# 🧳 Travel Dataset EDA

Exploratory Data Analysis (EDA) on Travel dataset using Python, Pandas, Seaborn, and Matplotlib.  
This project explores customer travel data, cleans missing values, and visualizes insights to understand product adoption patterns.

---

## 📊 Dataset Overview
- **Rows:** 4,128  
- **Columns:** 19  
- **Target Variable:** `ProdTaken` (1 = Product Taken, 0 = Not Taken)

### Key Features
- Age, Gender, Occupation, Marital Status  
- Type of Contact, City Tier, Duration of Pitch  
- Product Pitched, Preferred Property Star  
- Monthly Income, Number of Trips, Passport, Own Car  

---

## 🔧 Steps Performed
1. **Data Cleaning**
   - Fixed inconsistent values (`Fe Male` → `Female`)
   - Handled missing values (dropped NaNs)
   - Reduced dataset from 4,888 → 4,128 rows

2. **Univariate Analysis**
   - Countplots for categorical variables
   - Histograms for numerical variables
   - Distribution plots (Age, Monthly Income, etc.)

3. **Bivariate Analysis**
   - Scatterplots (Age vs Duration of Pitch)
   - Crosstabs (Marital Status vs ProdTaken)
   - Violin & Swarm plots (Age vs Gender/ProdTaken)
   - 3D Scatter plot (Age, Monthly Income, Duration of Pitch)

4. **Correlation Analysis**
   - Heatmap of numerical features

5. **Model Preparation**
   - Train-test split for classification
   - Target: `ProdTaken`

---

## ⚙️ Tech Stack
- Python 3.11  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Files
- `Travel_EDA.ipynb` → Full notebook with analysis  
- `Travel.csv` → Dataset (if small enough to include)  
- `requirements.txt` → Dependencies  
- `README.md` → Project overview  

---

## 🚀 Future Work
- Feature encoding for categorical variables  
- Build classification models (Logistic Regression, Random Forest, XGBoost)  
- Evaluate accuracy, precision, recall, and ROC curves  

---

## ✨ Author
**Prince**  
Bachelor in Medical Laboratory Technology (Expected 2028)  
Aspiring Healthcare Data Analyst | Python & Pandas Enthusiast  

---

## 📢 Showcase
> *“Just uploaded my Travel Dataset EDA project on GitHub!  
> Cleaned 4,128 records, visualized customer insights, and prepared data for predictive modeling.  
> Repo link: [GitHub link]  
> #Python #DataScience #EDA #Visualization #GitHubPortfolio”*
