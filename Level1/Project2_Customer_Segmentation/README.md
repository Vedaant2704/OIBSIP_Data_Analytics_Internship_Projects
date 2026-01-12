# Customer Segmentation Analysis

## About the Project
This project focuses on **customer segmentation** using data analysis and machine learning techniques to identify distinct customer groups.  
The primary objective is to segment customers based on **demographic and spending behavior**, enabling businesses to better understand their customers and implement data-driven marketing strategies.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship**.

---

## Objective
The key objectives of this project are:
- Analyze customer demographic and spending patterns  
- Segment customers into meaningful groups using clustering techniques  
- Identify behavioral differences among customer segments  
- Provide actionable insights to support targeted marketing and customer engagement  

---

## Dataset Overview
The dataset includes customer demographic details and purchase behavior metrics.  
Important features used in the analysis include:

- `income` – Annual income of customers  
- `age` – Age of customers  
- `mnttotal` – Total spending amount  
- Additional numerical features related to customer purchasing behavior and campaign responses  

Only relevant numerical attributes were selected to ensure accurate and effective clustering results.

---

## Tools and Technologies Used
The analysis was carried out using the following tools and technologies:

- **Python**
- **Pandas** for data preprocessing and analysis  
- **Scikit-learn** for K-Means clustering  
- **Matplotlib & Seaborn** for visualization  
- **Jupyter Notebook**
- **VS Code**

---

## Methodology
The project followed a structured data analysis workflow:

1. Loading and exploring the dataset  
2. Data cleaning and preprocessing  
3. Feature selection for clustering  
4. Feature scaling using `StandardScaler`  
5. Determining the optimal number of clusters using the Elbow Method  
6. Applying the K-Means clustering algorithm  
7. Visualizing and interpreting the resulting customer segments  

---

## Visualizations
To support analysis and interpretation, the following visualizations were created:

- Elbow Method plot for optimal cluster selection  
- Customer segmentation scatter plot (Income vs Total Spending)  
- Cluster size distribution  
- Average spending comparison across different clusters  

All generated visualizations are stored in the `visuals` directory.

---

## Key Insights
- Customers can be effectively segmented based on income and spending behavior.  
- One segment represents high-income, high-spending customers, classified as premium customers.  
- Another segment includes moderate-income customers with average spending patterns.  
- A distinct group consists of low-income, low-spending customers, indicating price sensitivity.  
- Spending behavior varies significantly across customer segments, highlighting the need for targeted strategies.  

---

## Business Recommendations
- Implement personalized marketing strategies for high-value customer segments.  
- Introduce loyalty programs for premium and regular customers.  
- Offer targeted discounts to price-sensitive customer groups.  
- Optimize marketing budget allocation based on customer segment value.  
- Regularly update customer segmentation models as new data becomes available.  

---

## Conclusion
This project demonstrates how **customer segmentation using clustering techniques** can uncover valuable insights from customer data.  
The analysis enables businesses to improve marketing effectiveness, enhance customer retention, and support strategic decision-making through data-driven insights.

---

## Author
**Vedaant Lodhi**  
Data Analyst Intern – Oasis Infobyte
