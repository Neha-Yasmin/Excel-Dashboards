# Excel-Dashboards
Bike Purchase
We have 13 attributes in the dataset, such as ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike. 

Our goal is to identify the type of people likely to purchase a bike.

All attributes, except ID and Purchased Bike, can be analyzed to find a pattern. The Purchased Bike field will provide the final output.

Limitations:
    1.	We have unequal records for each age group, which can skew the results in a certain direction.
    2.	The Marital Status field has incorrect values. Records labeled as 'single' have children.
    3.	The Cards attribute is not interactive.
    4.	The distribution of total records for the "Age Group" field is as follows: 57.3% are Middle-Aged Adults, 16% are Old, 1.1% are Senior Citizens, and 25.6% are Young Adults. Therefore, the majority of our customers belong to the Middle-Aged Adults category.
Before analyzing the dataset, it is crucial to study not only the attribute names but also the data present within them. It is important to understand what the data is all about. Only then can we begin the data analysis process.

Data Cleaning:
  1.	The ID column will not assist in our analysis since it merely provides a unique ID to individuals. However, we can use it to remove duplicates. We successfully removed 27 duplicates using the ID column and ensured that all remaining IDs are distinct.
  2.	We can now remove the ID column since it is not needed for our analysis.
  3.	We will change the values in the 'Marital Status' attribute from 'M' and 'S' to 'Married' and 'Single' respectively. Additionally, we will change the values in the 'Gender' attribute from 'M' and 'F' to 'Male' and 'Female' respectively. Lastly, we will change the data type of the 'Income' attribute to Numeric to facilitate calculations.
  4.	To arrange the values in chronological order, we will change the 'Commute Distance' field value from '10+ Miles' to 'More than 10 Miles'.
  5.	The 'Income' field has 16 distinct values, which can make visualization messy. Therefore, we will convert the values from discrete to continuous.
  6.	The 'Age' field has a wide range of values. To simplify analysis, we will aggregate the values. This concludes the data cleaning process.

  Our data is now ready for analysis.
    (Please note, the data present in the 'dump' is the original data and data present in the 'working sheet' is the edited data produced after data cleaning.
