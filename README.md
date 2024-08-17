<div align="center">
  <h1>📊 Customer Churn Analysis Project</h1>
</div>

## 📄 Overview
This project aims to analyze and predict customer churn using advanced **machine learning** techniques. By understanding the factors contributing to churn, businesses can proactively take steps to improve customer retention and reduce turnover.

## 📊 Dataset Information
- **Source**: The dataset contains various customer attributes, such as demographics, account information, and usage statistics.
- **Data Cleaning**: The dataset was meticulously cleaned, with missing values addressed, and outliers removed to ensure data integrity and reliability.

## 🔍 Methodology
1. **Data Collection and Cleaning**:
   - Comprehensive data gathering from customer records.
   - Applied rigorous data cleaning procedures to prepare the dataset for analysis.
   
2. **Exploratory Data Analysis (EDA)**:
   - **Correlation Matrix**: Examined relationships between customer attributes and churn.
   - **Histogram and Line Chart**: Visualized customer demographics and churn trends over time.

3. **Machine Learning Models**:
   - **📈 Logistic Regression**: Established a baseline model to predict churn probability.
   - **🌳 Decision Tree Classifier**: Used to create an interpretable model with rules based on customer attributes.
   - **🌲 Random Forest Classifier**: Leveraged an ensemble method to improve model robustness and accuracy.
   - **📊 SVM Model**: Employed Support Vector Machine for enhanced classification accuracy.

## 📈 Graphs and Visualizations

### 🔥 Correlation Matrix
![image](https://github.com/user-attachments/assets/59759f7f-5b82-4810-85d5-70034c1be4a3)
- **Key Insight**: The correlation heatmap reveals that higher customer balances strongly correlate with lower churn (-0.50), while an increased number of complaints is moderately associated with higher churn (0.20), indicating key factors influencing customer retention.

### 📊 Customer Segmentation Graph
![image](https://github.com/user-attachments/assets/037e6a19-1d09-415d-92ac-689fabfaf217)
- **Key Insight**: The graph shows that the churn distribution is relatively uniform across the three customer segments (SME (Small and Midsize Enterprise, Corporate, and Retail), indicating that churn is a consistent issue across all segments and not concentrated in any particular group.
  
### 📈 Scatter Plot
![image](https://github.com/user-attachments/assets/6d9c87e1-6cd8-4516-91a8-1c9e0187a5c9)
- **Key Insight**: The scatter plot highlights that customers with lower balances and incomes tend to have a higher likelihood of churning, as evidenced by the concentration of orange dots (representing churn) in the lower left quadrant of the graph. This suggests that financial status, specifically lower income and balance, could be a significant factor contributing to customer churn, indicating a potential area for targeted retention strategies.

### 🌡️ Cohort Analysis Heatmap
![image](https://github.com/user-attachments/assets/68a5fb43-bd9f-4249-81f2-238e62b2c3fd)
- **Key Insight**: This cohort retention heatmap shows how customer retention rates change over time. Key insight: Retention stabilizes around 33-34% after the initial quarter, highlighting the importance of focusing retention strategies on new and at-risk customers.

## 🌟 Key Takeaways
1. **Interpretability**: Decision Trees provide a clear and interpretable model for stakeholders to understand the factors influencing churn.
2. **Model Performance**: The Random Forest model showed superior accuracy, making it the best choice for predicting churn.
3. **Data Quality**: The effectiveness of the models relied heavily on the quality of data cleaning and preprocessing.
4. **Visualization Insights**: Histograms and line charts provided valuable insights into customer demographics and churn trends.
5. **Cross-Validation**: Ensured model generalization and avoided overfitting by using cross-validation techniques.

## 🚀 Room for Improvements
1. **Advanced Feature Engineering**: Introducing additional customer interaction metrics could enhance prediction accuracy.
2. **Hyperparameter Tuning**: Further tuning of model parameters could improve the SVM and Random Forest models.
3. **Ensemble Techniques**: Combining different models using ensemble methods may provide even better results.
4. **Handling Imbalanced Data**: Techniques like SMOTE could be applied to handle any data imbalance issues.
5. **Non-Linear Models**: Exploring non-linear models could capture complex relationships between features and churn.

## 💼 Applications
- **Customer Retention**: Utilize the models to identify high-risk customers and create targeted retention strategies.
- **Business Strategy**: Insights derived from the analysis can guide decision-making in marketing, sales, and customer service.
- **Predictive Analytics**: This methodology can be applied across various industries to predict customer behavior and optimize operations.

## 📂 Project Structure
- **/data**: Contains raw and processed datasets.
- **/notebooks**: Jupyter notebooks demonstrating the analysis process.
- **/scripts**: Python scripts for data processing and model training.
- **/outputs**: Visualizations and final analysis reports.
- **/images**: Contains the images used in this markdown file.
