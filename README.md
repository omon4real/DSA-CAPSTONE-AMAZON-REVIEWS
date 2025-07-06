# DSA-CAPSTONE-AMAZON-REVIEWS

## Project Overview
This project focuses on analyzing product name, category on Amazon to gain insights into customer behaviors, product performance and overall generated reviews available. Amazon provides a rich dataset that reflects real world customer experiences across various product categories.

### Objectives:
The primary objectives of this case study project is to explore patterns in customer reviews and evaluate the factors that influences product ratings. The analysis aims to help businesses and stakeholders understand how customers feedback can drive product improvement, marketing strategies and better customer services.

#### Data Source:
The primary source of data used is data.csv

##### Tools Used:
- used Excel for data cleaning, collection
- Pivot table for analyzing my data
- A chart to visualize my data

###### Data Preparation:
-	To clean my data, the first thing I did was to create a column i named product name 2 after the main product name . Since the product name was too long, I needed to reduce to the first four word. So I used the following formular to achieve that in my created column.
=TRIM(LEFT(B2,FIND(“#”, SUBSTITUTE(B2, “ “,”#”,4)& “#”)-1))

-	For my category, I created four columns to split the main category into four different sub-categories. And to achieve this after creating the columns, I highlighted the main category column and went to data tab>text to columns, a pop up box appears, I checked Delimited>Next>Order>typed | and clicked finish. After this, since my category has already been grouped so I hid the sub-category columns.
  
Please, I will continue with the steps I took to prepare my data if I have more time to do that.
