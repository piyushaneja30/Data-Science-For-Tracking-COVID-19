# Data-Science-For-Tracking-COVID-19

Covid19india.org has gathered data that helps to track the coronavirus worldwide. Python programming is used for the data science and machine learning in the project
1) Software used
-	Jupyter-Notebook- Jupyter- Notebook is used for predicting and visualizing coronavirus cases.

2) Machine Learning Models used-
-	Linear regression
-	Polynomial regression
-	SVR
-	Decision Tree
-	Random Forest

3)	Business Understanding
-Problem statement- We want to track Coronavirus cases and predict the number of confirmed cases for the next few days for India.

4)	Data understanding and Data collection-
-The data is collected from Covid19india.org. We have imported 21 CSV files to collect the data from the 1 st case of coronavirus to current cases. Data set is having 21 columns with 17364 entries in it.

5)	Data processing and Data cleaning
-The data is converted in the desired format. The gathered data cannot be used directly, so the data is cleaned accordingly to track coronavirus cases. The removal of corrupted data or unavailable data is done from the gathered data. State data and its visualization are used to demonstrate the state-wise coronavirus confirmed cases in India.
 
6)	Exploratory data analysis and visualization
-The fundamental of Data Visualization is to identify any trend or pattern from a large data set. The human brain can quickly process information when it is in a graph or a chart format. It allows us to interpret the data immediately. To understand what the information is about and what are its trend just by looking at the graph. Matplotlib libraries are used for plotting the graph.
![0](https://user-images.githubusercontent.com/41810625/127189752-ba78410d-c91a-4d72-ad5a-c79125b7e67f.png)

![00](https://user-images.githubusercontent.com/41810625/127189860-e49c0307-76a3-4ee7-8100-ca2a106ed0c2.png)

7)	Data Modeling
-	LINEAR REGRESSION
  ![1](https://user-images.githubusercontent.com/41810625/127188748-15d6f747-6dba-49ba-b6a5-bcd27e03b032.png)

-	POLYNOMIAL REGRESSION
  ![2](https://user-images.githubusercontent.com/41810625/127188834-54da5e91-28fe-41ef-bcec-87d223a76e3f.png)

-	SVR
  ![3](https://user-images.githubusercontent.com/41810625/127189426-f9a86155-25e4-40ca-b6ab-31384b903f51.png)
  
-	DECISION TREE
  ![4](https://user-images.githubusercontent.com/41810625/127189511-138b1eff-5cf9-4809-9837-cdc37e00241d.jpg)

-	RANDOM FOREST
  ![5](https://user-images.githubusercontent.com/41810625/127189591-72683b2c-2042-467b-8514-6ef1f76209a8.jpg)

8) RESULT


| Models               | Accuracy (%)  | Actual confirmed cases on Day 121  |	Predicted confirmed cases|
| ---------------------|:-------------:| :---------------------------------:| :-------------------------:|
| Linear regression    |   38.25       | 9847.0                             | 24278.14                   |
| Polynomial regression|   48.01       | 9847.0                             |   9754.87                  |
| SVR | are neat       |   96.14       | 9847.0                             |     9601.0                 |
| Decision Tree        |   100.0       | 9847.0                             |     9847.0                 |
| Random Forest        |   99.80       | 9847.0                             |  9754.87                   |
