#  ML Workflow Assignment

##  Problem Overview
You are given a dataset of customer orders and need to predict whether a customer will make a repeat purchase within 30 days.

---

##  Task 1

###  Label Column
**`repeat_purchase_flag`**

**Justification:**  
This is the target variable we want to predict, as it directly indicates whether a customer made a repeat purchase within 30 days (1 = Yes, 0 = No).

---

###  Data Leakage Column
**`discount_used_on_repeat_order`**

**Justification:**  
This column contains information about the repeat purchase itself, which would not be available at prediction time. Including it would leak future information into the model and lead to unrealistic performance.

---

##  Task 2

###  Step 1: Exploratory Data Analysis (EDA)

**Why it matters:**  
EDA helps in:
- Understanding data distribution  
- Identifying missing values  
- Detecting outliers  
- Finding relationships between variables  

This step ensures we fully understand the dataset before modeling.

---

###  Step 2: Data Preprocessing & Feature Engineering

**Why it matters:**  
This step includes:
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Creating new useful features  

Clean and well-prepared data improves model accuracy and reliability.

---

###   Step 3: Train-Test Split

**Why it matters:**  
Splitting the dataset into training and testing sets ensures that:
- The model is evaluated on unseen data  
- Overfitting is avoided  
- Performance metrics are realistic  

---

##  Conclusion
Before jumping into complex models like Gradient Boosting, it is essential to understand and prepare the data properly to ensure accurate and reliable predictions.
