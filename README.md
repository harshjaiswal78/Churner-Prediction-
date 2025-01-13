# Turning Data into Loyalty: Predicting and Preventing Customer Churn

In today’s competitive business environment, retaining customers is crucial for long-term success. 🔑 Churn analysis is a powerful technique to understand and reduce customer attrition by examining data to uncover patterns and reasons behind customer departures. By leveraging advanced analytics and machine learning 🤖, businesses can predict at-risk customers and identify key factors driving churn. This enables proactive strategies to enhance customer satisfaction and loyalty. ❤️

## Project Workflow

### 1. Server Setup and Data Access 🖥️
- Created a SQL Server in Azure Data Studio, accessible via IP and port.
- Managed and processed customer data efficiently in SQL Server.

### 2. Data Analysis in Power BI 📊
- Connected Power BI (on a Windows Virtual Machine) to the SQL Server to analyze customer demographics, payment methods, services, and churn trends.
- Processed data saved as SQL views for further use.

### 3. Predictive Modeling with Python 🐍
- Exported SQL views as CSV to VS Code for machine learning.
- Used Logistic Regression to predict future churners, analyzing critical factors driving churn.
- Results saved back to the SQL Server for integration.

### 4. Dashboard Creation 📈
- Built an interactive Power BI dashboard to visualize metrics like total customers, churn rate, and new joiners.
- Highlighted demographic, geographic, payment, and service-related factors impacting churn.
- Model Relationship Veiw 
![image](https://github.com/user-attachments/assets/a6c844df-93d3-4d4d-99ba-88a6d52d2c0b)
link to the dashboard : [Power BI Dashboard](https://app.powerbi.com/links/d6tnABSX3k?ctid=1b305a80-f34a-496b-b8a7-8691fb1ec04b&pbi_source=linkShare)



## Project Goals 🎯
- Establish an end-to-end ETL process for customer data.
- Visualize and analyze customer data across:
  - Demographic, Geographic, Payment & Account Info, Services.
- Study churner profiles to identify opportunities for targeted marketing campaigns. 📬
- Predict future churners using machine learning and generate actionable insights.

## Metrics Tracked 📌
- **Total Customers** 👥
- **Total Churn & Churn Rate** 🔄
- **New Joiners** 🆕

## Target Audience 🏢

Although this project focuses on churn analysis for a telecom firm, the techniques and insights are adaptable across industries. From retail 🛍️ to finance 💰 and healthcare 🏥, businesses can apply these methods to improve customer retention, turning data into actionable strategies for long-term success. 🌟
