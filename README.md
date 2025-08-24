# Customer Claim — Best Feature Analysis

This project analyzes a car-insurance dataset to find the **single most predictive feature** for whether a customer files a claim.  

---

## Steps Performed
1. **Load & Clean Data**  
   - Reads `car_insurance.csv`  
   - Fills missing numeric values with column means  

2. **Exploratory Analysis**  
   - Plots outcome distribution  
   - Boxplot of `credit_score` vs outcome  
   - Countplot of `driving_experience` vs outcome  
   - Correlation heatmap  

3. **Logistic Regression (One Feature at a Time)**  
   - Fits `outcome ~ feature` for each predictor  
   - Calculates in-sample accuracy  

4. **Result**  
   - Creates `best_feature_df` with:  
     - `best_feature` → top predictor  
     - `best_accuracy` → accuracy score 
