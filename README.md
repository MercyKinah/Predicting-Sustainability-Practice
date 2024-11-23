# Predicting-Sustainability-Practice
**Overview**

This project focuses on predicting the adoption and progression of sustainability practices among a selected group of companies. By leveraging data-driven methodologies, the project aims to identify key factors influencing sustainability practices, cluster companies based on similar behaviors, and predict future trends. The goal is to enable better decision-making for stakeholders, promoting sustainable growth and compliance with global environmental, social, and governance (ESG) standards.

**Project Structure**

The project comprises a comprehensive Jupyter Notebook outlining the entire data preprocessing process, feature engineering, model training, and evaluation.

**Data**

The dataset comprises dataset 100 companies for the duration of 7 years, totaling 700 data about the targeted companies from 2017 to 2023. The challenge involved merging each sustainability feature for the different years; some practices weren’t found in some years. Preparation included:
•	Establishing sustainability procedures of practice that each company uses during the years.
•	Handling missing values
•	Encoding categorical variables and the target column for sustainability prediction

**Preprocessing**

1.	Data Cleaning:
o	Remove duplicates and irrelevant records.
o	Handle missing values using imputation techniques.
2.	Data Transformation:
o	Normalize numerical features to ensure consistency.
o	Encode categorical variables using methods like one-hot encoding.
3.	Feature Engineering:
o	Create new variables like sustainability index scores or efficiency ratios.
o	Aggregate time-series data to capture trends.
4.	Clustering Preparation:
o	Scale data for clustering algorithms.
o	Reduce dimensionality if needed using PCA.

**Conclusion**

The project successfully predicts the adoption and progression of sustainability practices among target companies. By using clustering techniques like K-Means and predictive models, companies are categorized based on their sustainability performance and future trajectories. Insights from this analysis can guide businesses in adopting more effective sustainability strategies, aligning with global ESG standards, and improving their overall impact. The results promote better corporate responsibility and provide a roadmap for achieving long-term sustainable development.
