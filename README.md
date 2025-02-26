

# SALES DATA ANALYSIS

### Dashboard Link : https://app.powerbi.com/groups/me/reports/541ae81a-bffb-40b9-993f-8f00ad577d92?pbi_source=desktop
## Problem Statement

In this project, I dived into a large sales dataset to extract valuable insights, exploring sales trends over time, identifying the best-selling products, calculating revenue metrics such as total sales and profit margins, and created visualizations to present my findings effectively. This project showcases the ability to manipulate and derive insights from large datasets, enabling me to make data-driven recommendations for optimizing sales strategies.

COLUMN DESCRIPTION FOR SALES DATA ANALYSIS:
- ORDER ID
- PRODUCT
- QUANTITY ORDERED
- PRICE EACH
- ORDER DATE
- PURCHASE ADDRESS
- MONTH
- SALES
- CITY
- HOUR
### CLEANING THE DATA
#### Steps followed 

- STEP 1: I downloaded the dataset, uploaded it using the 'Get Data' option in Power BI, and then proceeded to transform the data.
- STEP 2: The column headers are identified in the first row and should be kept as headers by following the steps below.

![Image](https://github.com/user-attachments/assets/9bde5269-3385-4bd9-9610-83db37106dbc)

![Image](https://github.com/user-attachments/assets/4af57eaa-6119-4362-a045-5c1495afd14f)

![Image](https://github.com/user-attachments/assets/1965fbb0-d29a-4954-962b-c25366009db5)

- STEP 3: After promoting the headers, I navigated the 'Transform' tab and select 'Detect Data Type.' This action will automatically identifies the data type of each column and convert them as needed.
- STEP 4: I  then Split the datetime into date and time stamp
The aforementioned process starts with selecting the desired column.
Following the selection, the option to split the column becomes visible.

![Image](https://github.com/user-attachments/assets/7b98b28e-bf21-414a-b8a4-e52ff931e00b)

- I Choose the 'Split Column' option and selected the space as the delimiter.

![Image](https://github.com/user-attachments/assets/c4bfcdb6-5aaa-4fee-8f07-140193194337)

- Upon completing the data transformation, i made use of 'Close & Apply' located at the top left.
**Remember, this step is crucial after any data transformation process**

**VISUALIZATION OF THE DATA**                         

- STEP 1:Sales trend over time using the line chart 
- STEP 2: Best selling products using tree map
- STEP 3: Top 5 best selling product using stacked bar chart
- STEP 4: Top 5 cities by sales using map
- STEP 5: Weekly sales distribution by weekday using column chart
- STEP 6: Slicer is used to make this kind of visual

• To create a slicer visualization, I dropped the "Month Name" field
into the slicer option. 

• To display the slicer in a vertical list,  I accessed the
slicer settings and choose the option for a vertical column layout.

![Image](https://github.com/user-attachments/assets/d56c658d-9070-444e-8ac8-121f529f40d2)

- STEP 7: To find the revenue metrics:
• Total profit: Sum up the net profit from all sales transactions.

• Sales quantity: Calculate the total number of units sold.

• Profit margin: Compute the ratio of net profit to total revenue, usually expressed as a percentage.

**REVENUE = SUM(SALES)**

**PROFIT MARGIN = (( TOTAL SALES -TOTAL COST )/TOTAL SALES)*100***

- STEP 8: The report was then saved accordingly.
 
 
 # Report Snapshot (Power BI DESKTOP)

 
![Image](https://github.com/user-attachments/assets/7d4dbda4-9494-4566-9159-138907f7e0f7)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] SALES
   
Total sales = 209,079

Highest month in terms of sales = December

Best selling products = AAA Batteries

Average quantity ordered per month = 17,000

Highest regional sales (city) = San francisco
