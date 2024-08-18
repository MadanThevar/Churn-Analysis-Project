![Churn Analysis](https://raw.githubusercontent.com/MadanThevar/Churn-Analysis-Project/main/1591702479502.webp)

<div align="center">
  <h1>📊 Customer Churn Analysis Project</h1>
</div>

## 📄 Overview
This project utilizes advanced data analysis and machine learning techniques to predict customer churn and enhance retention strategies. Key tools include Python, Pandas, Matplotlib, Seaborn, Scikit-learn, and Tableau for interactive visualizations. The project covers comprehensive data cleaning, exploratory data analysis, and robust modeling, including Logistic Regression, Decision Trees, and Support Vector Machines (SVM). Visualizations, such as cohort retention heatmaps and customer segmentation graphs, alongside Tableau dashboards, provide actionable insights for data-driven decision-making in customer retention.

## 📊 Dataset Information
- **Source**: The dataset contains various customer attributes, such as demographics, account information, and usage statistics had to remove personal records for confidentiality and inserted fictional data to avoid someones personal data information from being leaked.
- **Data Cleaning**: The dataset was meticulously cleaned, with missing values addressed, and outliers removed to ensure data integrity and reliability.

## 🔍 Methodology
1. **Data Collection and Cleaning**:
   - Comprehensive data gathering from customer records.
   - Applied rigorous data cleaning procedures to prepare the dataset for analysis.
   
2. **Exploratory Data Analysis (EDA)**:
   - **Correlation Matrix**: Examined relationships between customer attributes and churn.
   - **Histogram and Line Chart**: Visualized customer demographics and churn trends over time.

## 📈 Graphs, Visualizations & 🤖 Machine Learning Models

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
- **Key Insight**: This cohort retention heatmap shows how customer retention rates change over time. Retention stabilizes around 33-34% after the initial quarter, highlighting the importance of focusing retention strategies on new and at-risk customers.

### 📈 Logistic Regression
- **Description**:The Logistic Regression model achieved an outstanding accuracy of 99.81%, with perfect precision and recall for non-churned customers and nearly perfect recall (0.99) for churned customers, ensuring very few missed churn cases. The balanced performance across both classes, even in an imbalanced dataset, highlights the model's reliability. This strong predictive ability allows for more accurate identification of at-risk customers, enabling targeted retention strategies to effectively reduce churn.
- **Accuracy**:
<img width="383" alt="Screenshot 2024-08-17 at 16 00 43" src="https://github.com/user-attachments/assets/641a687c-c82f-4c7b-8755-6e371414e27c">

### 🌳 Decision Tree Classifier
- **Description**: The Decision Tree model achieved a strong accuracy of 98.39%, with high precision (0.99) and recall (0.99) for non-churned customers, and slightly lower but still effective precision (0.94) and recall (0.93) for churned customers. This balanced performance, with a weighted F1-score of 0.98, makes the model reliable for predicting churn across both classes. Additionally, the model’s high precision helps minimize false positives, ensuring that resources are efficiently allocated to truly at-risk customers, thereby improving the overall effectiveness of retention strategies.
- **Accuracy**:
<img width="390" alt="Screenshot 2024-08-17 at 16 03 59" src="https://github.com/user-attachments/assets/cd4cfe20-bceb-4f6d-bcce-4fbaa3d0b574">

### 🌲 Random Forest Classifier
- **Description**: The Random Forest model achieved a solid accuracy of 97.55%, with perfect recall (1.00) for non-churned customers and high precision (0.98) for churned customers, although recall for churned customers is lower at 0.81. This results in a strong weighted F1-score of 0.98, making the model effective at balancing between identifying non-churned and churned customers. The model’s high recall for non-churned customers ensures that almost all non-churned customers are correctly identified, reducing the likelihood of unnecessary interventions. Additionally, its robustness against overfitting due to the ensemble nature of Random Forests makes it particularly beneficial for improving the generalization of churn prediction models across different customer segments.
- **Accuracy**:
<img width="375" alt="Screenshot 2024-08-17 at 16 08 47" src="https://github.com/user-attachments/assets/3b398b50-5316-40c0-9feb-aba3f3ce4e8d">

### 📊 SVM Model
- **Description**: The Support Vector Machine (SVM) model achieved an impressive 99.48% accuracy, with perfect precision and recall for non-churned customers and high performance for churned customers, reflected in a robust F1-score of 0.98. The SVM model’s ability to accurately identify at-risk customers while minimizing false positives makes it an effective tool for optimizing customer retention strategies and improving overall retention rates.
- **Accuracy**:
<img width="382" alt="Screenshot 2024-08-17 at 16 11 23" src="https://github.com/user-attachments/assets/72b7d1d8-5110-49a6-93f1-53f26a4afa04">

## 📊 Tableau Dashboard
<img width="1201" alt="Screenshot 2024-08-17 at 16 34 04" src="https://github.com/user-attachments/assets/357b1791-9890-4e45-8ddf-ae3fb88fa767">

### 🔍 Key Insights:
1. **Churn Rate**: Overall churn rate is 12.19%, necessitating targeted retention strategies.
2. **Income & Age**: Middle-aged and low-income customers have higher churn rates, requiring personalized engagement.
3. **Complaints**: Even customers with low complaints show significant churn, indicating potential dissatisfaction.
4. **Tenure Trends**: Newer customers are at higher risk of churn, emphasizing the need for strong onboarding.
5. **Segmentation**: SME and Corporate segments dominate the customer base, suggesting tailored retention efforts for these groups.

### ⚖️ Adjustments and Calculated Fields:
1. **Income & Age Groupings**: Created calculated fields for age and income ranges to analyze churn across different customer demographics.
2. **Complaint Level Segmentation**: Segmented customers based on complaint levels using calculated fields to visualize the impact of complaints on churn.
3. **Customer Tenure Calculation**: Applied quick table calculations to track and visualize customer tenure trends over time.
4. **Churn Rate Calculation**: Calculated overall churn rate by dividing churned customers by total customers, providing a clear metric for analysis.
5. **Customer Segmentation by Category**: Categorized customers into SME, Corporate, and Retail segments using calculated fields to highlight the distribution of the customer base.

## 🌟 Key Takeaways
1. 🔍 **High Predictive Accuracy**: The Support Vector Machine (SVM) model achieved outstanding accuracy, making it a top choice for accurately predicting customer churn and reducing false positives.
2. 📊 **Comprehensive Data Insights**: Visualizations like the Correlation Heatmap and Scatter Plot revealed crucial factors like customer balance and income that strongly correlate with churn, guiding more targeted retention strategies.
3. 🌳 **Model Interpretability**: The Decision Tree model provides clear, interpretable decision rules, allowing stakeholders to easily understand the factors driving customer churn.
4. ⚖️ **Balanced Model Performance**: The models demonstrated well-rounded performance with high precision, recall, and F1-scores, ensuring reliable identification of at-risk customers while minimizing unnecessary interventions.
5. 📈 **Strategic Retention Focus**: Cohort Analysis Heatmaps highlighted critical periods for customer retention, enabling businesses to focus their efforts on the most vulnerable customer segments and improve overall retention rates.

## 🚀 Room for Improvements
1. **🔧 Advanced Feature Engineering**: Introducing new features like customer engagement metrics and interaction terms to capture complex relationships influencing churn.
2. **⚙️ Hyperparameter Tuning**: Optimizing model parameters through grid search or boosting techniques to enhance accuracy and generalization.
3. **⚖️ Addressing Data Imbalance**: Applying techniques like SMOTE (Synthetic Minority Oversampling Technique) or adjust class weights to improve the recall for churned customers and better handle class imbalance.
4. **🔍 Model Interpretability**: Using SHAP(SHapley Additive exPlanations values) or LIME(Local Interpretable Model-agnostic Explanations) to enhance the interpretability of complex models, helping to understand feature contributions.(Advanced Models)
5. **🔄 Cross-Validation**: Implementing K-Fold cross-validation to ensure the model generalizes well to different subsets of data, improving robustness.


## 💼 Applications
1. **🔍 Precision Targeting**: Use machine learning models to identify and engage high-risk customers with personalized retention strategies before they churn.
2. **🤖 AI-Driven Engagement**: Implementing AI-powered chatbots and recommendations to proactively address customer needs, enhancing satisfaction and loyalty.
3. **📊 Dynamic Segmentation**: Continuously segment customers based on behavior, allowing tailored strategies that evolve with customer needs.
4. **🌐 Omni-Channel Optimization**: Ensure a seamless customer experience across all platforms, reducing churn caused by inconsistent service.
5. **🔄 Predictive Maintenance**: Monitor customer behavior with time-series analysis to detect and address churn risks early, maintaining long-term engagement.


## 📊 Dataset Information

The full dataset for this project is available for download on Google Drive. Click the link below to access the dataset:

[Dataset Access](https://drive.google.com/file/d/11cPBlPd6nBiJJ0jd-A0zxrXcihpTHmqv/view?usp=drive_link)

