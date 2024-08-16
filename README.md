<div align="center">
  <h1>📊 Churn Analysis Project</h1>
</div>

## 📄 Overview
A project to predict customer churn using machine learning models like SVM and Logistic Regression, with key insights driving targeted retention strategies. Features include cohort analysis and an interactive Tableau dashboard for data-driven decision-making.

## 📊 Dataset Information
- **Source**: The dataset includes customer demographics, service usage, and account information and added some fictional data to avoid leaking customer information details.
- **Data Cleaning**: I meticulously cleaned the data, handling missing values, outliers, and ensuring the dataset was ready for modeling.

## 🔍 Methodology
1. **Data Collection and Cleaning**:
   - Collected extensive data from customer records.
   - Processed and cleaned the data, ensuring its suitability for analysis.
   
2. **Exploratory Data Analysis (EDA)**:
   - **Correlation Matrix**: Visualized relationships between various customer features.
   - **Feature Importance**: Identified the most critical features influencing customer churn.

3. **Machine Learning Models**:
   - **📈 Logistic Regression**: A baseline model providing insights into the likelihood of customer churn.
   - **🌳 Decision Tree Classifier**: A model that provides interpretable rules to predict churn.
   - **📊 SVM Model**: A Support Vector Machine model was trained to enhance classification accuracy.
   - **🌲 Random Forest Classifier**: An ensemble model that improves prediction performance by combining multiple decision trees.

## 📈 Graphs and Visualizations

### 🔥 Correlation Matrix
![image](https://github.com/user-attachments/assets/96604647-5f97-4f87-9983-0d790301aa1e)
- **Description**: This correlation heatmap illustrates the relationships between various customer features and churn. Notably, there is a moderate negative correlation between Churn Flag and Balance (-0.50), suggesting that customers with lower balances are more likely to churn, while other features show weaker correlations with churn. This insight highlights the importance of financial metrics in predicting customer churn.

### 📊 Feature Importance
![Feature Importance](./images/feature_importance.png)
- **Description**: The bar chart ranks the features based on their importance in predicting churn, highlighting the key factors that influence customer decisions.

### 📈 SVM Model - Classification Boundary
![SVM Model](./images/svm_boundary.png)
- **Description**: The SVM model's decision boundary is visualized, showcasing how well it separates churned customers from non-churned ones.

### 🌳 Decision Tree - Visualization
![Decision Tree](./images/decision_tree.png)
- **Description**: This decision tree provides a visual representation of the rules used to predict churn, offering an easy-to-interpret model.

## 🌟 Key Takeaways
1. **Logistic Regression Performance**: Provided a solid baseline with interpretable coefficients.
2. **Decision Tree Interpretability**: The decision tree model is easy to understand and interpret, making it useful for non-technical stakeholders.
3. **Random Forest Accuracy**: The random forest model offered the best accuracy, leveraging the power of multiple trees.
4. **SVM Precision**: The SVM model excelled in distinguishing between churned and non-churned customers.
5. **Data Quality**: High-quality, well-cleaned data is essential for reliable model predictions.

## 🚀 Room for Improvements
1. **Feature Engineering**: Additional features such as customer interaction history could improve model accuracy.
2. **Model Tuning**: Hyperparameter tuning could further enhance the performance of complex models like SVM and Random Forest.
3. **Ensemble Methods**: Combining models using ensemble techniques might yield even better results.
4. **Cross-Validation**: Implementing cross-validation ensures the model's robustness and generalizability.
5. **Handling Imbalanced Data**: Exploring techniques like SMOTE could improve model performance on imbalanced datasets.

## 📈 Applications
- **Customer Retention**: Use the models to identify high-risk customers and implement targeted retention strategies.
- **Business Strategy**: Insights from the analysis can inform marketing and customer service decisions.
- **Predictive Modeling**: The approach can be applied to other industries for predictive customer behavior analysis.

## 📂 Project Structure
- **/data**: Contains the raw and cleaned datasets used in the analysis.
- **/notebooks**: Jupyter notebooks showcasing the data analysis process and model implementation.
- **/scripts**: Python scripts used for data processing and model training.
- **/outputs**: Final visualizations and analysis reports.
- **/images**: Contains the images of the graphs used in the markdown file.

## 📚 References
- **Final Report**: [Download PDF](./Final%20report%20document.pdf)
- **HTML Report**: [View Project](./Churn%20Analysis.html)
