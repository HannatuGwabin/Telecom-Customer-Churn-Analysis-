# Telecom-Customer-Churn-Analysis-

Telecom Customer Churn Analysis Using Python and Tableau.


![image](https://github.com/HannatuGwabin/Telecom-Customer-Churn-Analysis-/assets/115185829/9eabef9b-491f-410e-9be0-a64179153ed2)




The telecoms sector is a fiercely competitive business; thus, telecom companies must maintain their competitiveness by being inventive and emphasizing technology and customer experience. Churn is a problem that affects practically every sector. However, given that many people think the telecommunications sector has peaked, it is particularly pertinent to that industry. Customer churn is one of the most critical metrics for a growing business to evaluate. Customer retention is vital to a company's ability to expand and succeed. Understanding the causes of churn in the telecom industry is crucial for reducing customer turnover rates, effectively competing, and increasing revenue.

As a data scientist, it is my responsibility to conduct a thorough analysis of the Telecom churn dataset to know the reason why these customers are churning by providing the following answers to these questions:

•	What is the total of lost revenue?

•	What is the customer profile for a customer that churned, joined, and stayed? Are they different?

•	What type of contract were churned customers on?

•	Were churned customers getting any offers?

•	What internet type were churned customers on?

•	Did churn customers have premium tech support?

•	Did churn customers have online security?

•	Did churn customers have a device protection plan?

•	What is the distribution of churned customers across the different cities?

•	What seem to be the key drivers of customer churn?

•	Is the company losing high-value customers? If so, how can they retain them?


## Objectives

•	Identify and extract key performance indicators (KPIs) to improve the Telecom company operations and support data-driven decision-making.

•	 An easy-to-use visualization tool that can present data to stakeholders, making it simpler to explain insights and suggestions to lower customer churn.


## Study Approach

I got the dataset from Maven Analytics, which contains information about customer demographics, Internet Service, Payment Methods, Customer Status, and other essential features for the Telecom Company. I performed data preparation, cleaning, and transformation using Python. The dashboard background image for the dashboard was made using PowerPoint. The analysis, visualizations, and dashboard were designed using Tableau. 

## Steps Taken in Python

✅ Import Libraries (pandas, numpy, matplotlib, and seaborn).

✅ Extract the data from the CSV file and load it into Pandas Dataframe.

✅ Data Inspection (Check for Duplicates, Overview of the Data, and Check for missing Values).

✅ Data Cleaning and Transformation (fill in the missing values).

data['Avg_Monthly_Long_Distance_Charges'].fillna(0, inplace=True)

data['Multiple_Lines'].fillna('Unknown', inplace=True) 

✅ Saved the cleaned data for the next task.


## Steps Taken in Tableau

✅ Created Key performance indicators (KPI) to measure customer attrition.

✅ Created a calculated field to calculate the total number of Customer IDs using 'COUNTD(Customer ID)' 

✅ Created a calculated field to calculate the Churn rate using COUNT(IF[Customer Status] = “Churned” THEN [Customer ID] END / Count([Customer ID])

✅ Created a calculated field to calculate the total number of Stayed Customers using COUNT(IF[Customer Status] =  “Stayed”  THEN [Customer ID] END

✅ Created a calculated field to calculate the total number of Churned Customers using COUNT(IF[Customer Status] =  “Churned”  THEN [Customer ID] END

✅ Created a calculated field to calculate the total number of Joined Customers using COUNT(IF[Customer Status] =  “Joined”  THEN [Customer ID] END

✅ Data Visualization

✅ Data Insights and Recommendations to retain customers.


## DATA INSIGHTS

•	Dataset: The dataset contains 7,043 customers.

•	Customer Status: The customers' status is grouped into three categories: stayed customers, with a total of 4,720; churned customers, with a total of 1,869; and joined customers, with a total of 454.

•	Churn Rate: The churn rate is 26.5%, indicating a significant loss of customers.

•	Churned Revenue: The Telecom company lost about $3.68M due to churned customers, indicating a significant loss of revenue.

•	Churned City: San Diego has the highest churned customers at 53%, followed by Los Angeles with 22%.

•	Churned Contract: 89% of churned customers were on the month-to-month contract.

•	Offer: 56% of churned customers had no promotional offers.

•	Internet Type: 66% of churned customers used fiber optic internet type.

•	Premium Tech Support: 77% of churned customers did not have premium tech support.

•	Online Security Service: 83% of churned customers did not have online security services.

•	Device Protection Plan: 69% of churned customers had no device protection plan.

•	Key Drivers Of Churners: The most significant proportion of churned customers' reasons for churning is related to the competitor having better devices (29%), the competitor making a better offer (29%), the attitude of the support person (20%) and competitor offering more data (11%).



## RECOMMENDATIONS TO RETAIN CUSTOMERS

•	Offer memberships and rewards for loyalty, encouraging customers to keep doing business with the company.

•	By providing quicker response times and attending to customer complaints and concerns, improving customer service and relationships can help lower churn rates.

•	Ensure that the customer support team is well-trained.

•	Cities with the highest churn rates require the most attention in control measures. San Diego and Los Angeles, for instance.

•	Make strategic decisions while learning about what your competitors do differently, such as offering superior devices, more data, premium tech support, online security, and device protection plans to retain customers.

•	Improve products so these customers can have value for their money to retain customers.

•	Improve marketing strategies and create more awareness of products and services rendered.

•	Be honest about your products and services.

•	Employ lengthier contracts as an alternative to month-to-month contracts. Customers may have adequate time to use the product and experience its benefits. They are more likely to commit to the product after seeing its benefits.




## CHURNED CITIES


![Screenshot (48)](https://github.com/HannatuGwabin/Telecom-Customer-Churn-Analysis-/assets/115185829/b4ff2547-ebc1-4293-9409-8af5a0355f6b)




## TELECOM CUSTOMER CHURN DASHBOARD



![Screenshot (49)](https://github.com/HannatuGwabin/Telecom-Customer-Churn-Analysis-/assets/115185829/4411db11-e1fb-4f72-b3b7-dc9f00915732)




