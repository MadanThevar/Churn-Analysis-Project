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

## 📈 Graphs, Visualizations & Machine Learning Model Accuracies

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

### 📈 Logistic Regression
- **Description**:The Logistic Regression model achieved an outstanding accuracy of 99.81%, with perfect precision and recall for non-churned customers and nearly perfect recall (0.99) for churned customers, ensuring very few missed churn cases. The balanced performance across both classes, even in an imbalanced dataset, highlights the model's reliability. This strong predictive ability allows for more accurate identification of at-risk customers, enabling targeted retention strategies to effectively reduce churn.
- **Accuracy**:
<img width="383" alt="Screenshot 2024-08-17 at 16 00 43" src="https://github.com/user-attachments/assets/641a687c-c82f-4c7b-8755-6e371414e27c">


### 🌳 Decision Tree Classifier
- **Description**: The Decision Tree model achieved a strong accuracy of 98.39%, with high precision (0.99) and recall (0.99) for non-churned customers, and slightly lower but still effective precision (0.94) and recall (0.93) for churned customers. This balanced performance, with a weighted F1-score of 0.98, makes the model reliable for predicting churn across both classes. Additionally, the model’s high precision helps minimize false positives, ensuring that resources are efficiently allocated to truly at-risk customers, thereby improving the overall effectiveness of retention strategies.
- **Accuracy**:
<img width="390" alt="Screenshot 2024-08-17 at 16 03 59" src="https://github.com/user-attachments/assets/cd4cfe20-bceb-4f6d-bcce-4fbaa3d0b574">

### 🌲 Random Forest Classifier
- **Description**: Leveraged an ensemble method to improve model robustness and accuracy.
- **Accuracy**: ![Random Forest Accuracy](./images/random_forest_accuracy.png)

### 📊 SVM Model
- **Description**: Employed Support Vector Machine for enhanced classification accuracy.
- **Accuracy**: ![SVM Accuracy](./images/svm_accuracy.png)

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
