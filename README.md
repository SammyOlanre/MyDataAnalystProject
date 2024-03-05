# MyDataAnalystProject

**INTRODUCTION**

Here is a comprehensive report that encapsulates the essence of the two intriguing projects offered by MeriSKILL as a Data analyst intern. These projects, centered within the realm of data analytics, are meticulously designed to unravel patterns and insights concealed within intricate datasets. The focus of these projects includes:

1. Sales Analysis: A deep dive into sales data, aimed at extracting valuable insights to enhance strategic decision-making.

2. HR Analytics: Delving into the world of human resources, with a keen eye on data analysis to optimize talent management and organizational performance.

**PROJECT 1: SALES DATA**

**PURPOSE:**
To Analyze sales data to identify trends, top-selling products, and revenue metrics for business decision-making.

**DESCRIPTION:**
In this project, I dive into a large sales dataset to extract valuable insights. Exploring sales trends over time, identifying the best-selling products, calculating revenue metrics such as total sales and profit margins, and creating visualizations to present your findings effectively. 

The datasets underwent meticulous cleaning and analysis using Excel before being imported into Power BI through Power Query. Noteworthy transformations were applied, including header promotion, column splitting by delimiter, and data type adjustments.

This project showcases my ability to manipulate and derive insights from large datasets, enabling you to make data-driven recommendations for optimizing sales strategies.

Column Description For Sales Data Analysis:
• Order ID
• Product ID
• Quantity Ordered
• Price Each
• Order Date
• Purchase Address
• Month
• Sales
• City
• Hour

**TRANSFORMATION OF DATA**

STEP 1:
I downloaded the dataset, uploaded it using the 'Get Data' option in Excel, and then proceeded to transform the data.

STEP 2:
The column headers are identified in the first row and were promoted. The data were 'Transformed using the transform tab in the Power Query tab. This action will automatically identify the data type of each column and convert it by adding columns, changing data types, and splitting by delimiters as needed. 

![transform sales data](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/647e58fb-56fb-4b61-9fd1-467884e8d8c1)

STEP 3:
After loading the data, I use the pivot table to extract the significance from the large, detailed data set as shown below;

![Pivot table excel](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/8846274e-c930-4237-96e6-fb997e18a1e5)

![Pivot table sales 2](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/32a809fa-0aa5-4745-a42c-f011cb2168ea)


**VISUALIZATION OF DATA**
The transformed data was then imported to the Power Query in Power BI and was loaded. Here, I performed significant visualizations, including Sales trends over time using the line chart, The best-selling products using a tree map, The top 5 best-selling products using a stacked bar chart, and Weekly sales distribution by weekday using a column chart.

To visualize the Months and Days in chronological data using the slicer visual, the parent data for the Order_date were revisited and split into delimiters. The column data type was transformed to Day and month which shows the day and Month number as seen below.

![snip](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/8bfd448d-9674-423f-b655-83257a053ca3)

![transform sales data](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/13709841-ff7c-45ff-852e-6b569cf8b378)

To find the revenue metrics:
• Total profit: Sum up the net profit from all sales transactions.
• Sales quantity: Calculate the total number of units sold.
• Profit margin: Compute the ratio of net profit to total revenue, usually expressed as a percentage.

1. I select the "Card" visualization type, then drag and drop the "Sales" into the designated field. Convert it to the "SUM" aggregation.
2. Additionally, I adjust the display units to show values in millions, billions, trillions, or hundreds, and customize the number of decimal places as needed.

![Card](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/fa0345fd-a72a-43ba-a855-3798a3558b00)

Order visualizations as shown below were also created;

**The map Visualization**
Using a Power BI map is a great way to visualize data that represent locations. With visually appealing maps and easy-to-understand content, your users will be able to gain more insight into your data

Before using map visuals, you need to enable the map visual from the settings in Power BI.

Using the map visually, I was able to visualize the cities with the most selling products
![Map viz](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/fd1c74c7-23db-460b-8241-ddebf2836015)

I also plotted the sales trends over time using the line chart, The best-selling products using a tree map, The top 5 best-selling products using a stacked bar chart, and Weekly sales distribution by weekday using a column chart as shown below.

The Sales trend over time using the line chart
![Sales by month](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/c34ff9f4-23a8-4385-b9df-5a99569dc731)


The Best 5 selling products using a tree map
![sales viz top 5](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/04ecc620-6b70-4032-bfc5-ead0e476acbd)


**SALES DASHBOARD FINAL**
![Full viz sales data](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/62dd6eea-3d63-4a62-ad33-ea1b58035634)


**KEY INSIGHTS**

December witnessed the highest sales at 24,984, marking a remarkable 157.33% increase compared to the lowest sales in January, recorded at 9,709.

Additionally, visual representations highlighted the AAA battery as the product with the highest quantity ordered, while Wired Headphones received the least orders.

The top 5 products with the highest sales counts were iPhone, 27in 4k Gaming Monitor, Google Phone, MacBook Pro laptop, and Thinkpad laptop, with the MacBook Pro laptop being the most expensive.

Leveraging the map visually, I showcased the top 5 cities contributing to the highest sales in the United States, namely San Francisco, Los Angeles, New York, Boston, and Atlanta.

This project underscores my adeptness in manipulating and extracting insights from extensive datasets, enabling data-driven recommendations for optimizing sales strategies.


**PROJECT 2: HR ATTRITION**

**DESCRIPTION**
The project entails an HR attrition dataset providing an overview of the demographics insights, the turnover analysis, and employee wellness. While working on the datasets, I was saddled with cleaning them datasets by deleting redundancy, renaming some columns, dropping duplicates, cleaning individual columns, removing the NaN values from the datasets, and checking for more transformations.  Visualize the data with Power BI, while plotting a correlation map for all numeric variables, Marital status, job role, Gender, Total working year, Distance from home, Number of companies worked, etc.

**PURPOSE** 
To analyze the attrition data by Demographic insights, turnover information, and employee wellness.

**Data Cleaning:**
• Deleting redundant columns.
• Renaming the columns.
• Dropping duplicates.
• Cleaning individual columns.
• Remove the NaN values from the dataset
• Check for some more Transformations

**Data Visualization:**
• Plot a correlation map for all numeric variable Overtime
• Marital Status
• Job Role
• Gender
• Education Field
• Department
• Business Travel
• Relation between Overtime and Age
• Total Working Year
• Education Level
• Number of Companies Worked
• Distance from Home

I downloaded the dataset and uploaded the data using the "Get Data" option in Power BI. Utilized the "Transform" option to check for any null values in the dataset.

A separate column was created to decipher the count of attrition to the Total employees which is shown below;

This will yield the desired results: if "Attrition" is "Yes," the count is 1; if it's "No," the count is 0.

Summing all the 1s gives the total attrition count that is 237, And subtracting this from the employee count yields the count of active employees which is 1233

![Attrition formula](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/304ef5a0-5c47-45a5-b327-a25ba328cbb6)

**Grouping Data**
I aggregate certain values together to form meaningful subsets.
![Job Level groups](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/53da2fad-8f91-4baa-8044-e236263ba75c)
![groups age](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/f75c5ee2-c426-4c91-93e4-e920770f8ff4)

**VISUALIZATION OF DATA**
**DEMOGRAPHICS**

Total Employees, Attrition Count, and Active employees: Using the card to determine as shown below;

![attr counnt](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/72dd3d20-f719-45ff-a9af-cef6dd0a6f8c)

![Active employee](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/b723cde0-8103-46b5-b223-d74f7b9d64b6)

![Total employee](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/60b686fe-f849-4ff5-87c8-c180caed5f76)

Total attrition by education field by the clustered bar chart

![attition by education](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/724d92b4-cebf-4837-9138-6aa43262aff5)

Using data groups to make better visuals. I create a few visuals using the concept of grouping to organize and display the data effectively as below.

![Age groups](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/e3305bc2-6c01-4573-9e6f-d85a052e6080)

A slicer is used to make this kind of visualization; The slicer can either be displayed as a dropdown or vertical column layout in settings

![slicer marital](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/14c5720b-0336-4276-9695-3b99dc0be6f8)


**FINAL DEMOGRAPHICS DASHBOARD**

![Demographics final](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/4d30a152-f5c0-4a0f-aaea-92199e523985)


**TURNOVER ANALYSIS**

Total attraction by Business Travel

![Business travel](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/8dcf98f0-8c38-4576-be58-9e04b93a8161)

Total attrition by department using the donut chart

![Donut attrition](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/62dc894d-c615-4f2c-8146-55513f60c920)

Total attrition by years in current role using a stacked column chart

![attriction stacked](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/01a1424b-e5e1-4f84-bd96-3bb4f143bbd7)

Total attrition by job role filtered by Gender

![Job role](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/dbef4b18-46f6-4192-9014-8b3ca28639a3)

**FINAL TURNOVER ANALYSIS I**

![Turnover analysis](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/a28a8bec-b25c-44b6-8efe-fc5ae05925bd)


**TURNOVER ANALYSIS II**
Tota attrition by Job level: The job levels which were given in numbers were also grouped and plotted as shown below;

![Attrition by Job level](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/b099daa3-ca14-4fdb-8844-2e5a3a818cbf)


Total attrition by performance and rating.
The concept of grouping was also imbibed here before visualizing the data as shown below;

![Performance rating grouping](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/5c0645bf-bee4-470b-ac7e-b1398d8fdbf0)

![Performance rating](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/c3c22c58-2350-4b4d-b705-514942f50dc8)

Average monthly Income and Attrition by job role;

![Average monthly income](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/6365af70-99c3-4e9d-b6dd-c10a4e5de9c5)


**FINAL TURNOVER ANALYSIS II**

![Turnover analysis II](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/7f900556-fc4b-4c38-9055-c033e9e29e60)


**EMPLOYEE WELLNESS**

Relationship satisfaction is grouped as dissatisfied, very dissatisfied, satisfied, and very satisfied as visualized below;

![Employee Wellness](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/a8a450dc-37ab-44a7-97c1-d175bd5c7381)


Total Attrition by Work-Life Balance
On the work-life balance grouping, 1 represents "Bad" 2 stands for "Average" 3 signifies "Good" and 4 indicates "Excellent".

![Work life bal groups](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/4826ecc7-43ac-4045-9d1a-895f7595b0ae)

Total attrition by job involvement.
• The Job involvement is also grouped as very low, low, Moderate, and High.

![Job Involvemnet group](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/518ec1e7-5d3d-414a-aa53-2051339b0aa4)


**FINAL EMPLOYEE WELLNESS DASHBOARD**

![Employee Wellness](https://github.com/SammyOlanre/My-SQLSERVER-PROJECT/assets/87617278/a8eb7813-b3b3-46a9-ab38-4624b8695592)

In this dashboard, grouping plays a crucial role in organizing and presenting the data effectively. The design of the dashboard is tailored to utilize the power of grouping for enhanced data visualization and analysis.

**KEY INSIGHTS**
**DEMOGRAPHICS**
The analysis discerns that the age group 31-45 exhibits the highest Attrition Count, surpassing the 46-60 age group by 202.94%, with the latter recording the lowest Attrition Count at 34. This implies that the highest employee departures from the organization occur between the ages of 31-45, accounting for 43.46% of the total attrition.

Specifically, the age group 31-45 commands the highest Sum of Attrition Count at 103, followed by 18-30 at 100 and 46-60 at 34. Notably, the 31-45 age group contributes to 43.46% of the total Sum of Attrition Count.

Furthermore, a significant portion of the total attrition, comprising 63%, involves male employees departing from the organization, while 37% pertains to female employees.

The analysis extends to marital status, revealing that 51% of single employees (31% male and 21% female) exhibit a departure from the organization, contrasting with 35% for married employees and 14% for divorced employees.

Moreover, employees from the Life Sciences field, totaling 89, show a higher rate of departure compared to other educational fields, with Human Resources exhibiting a lower count of 7.

In summary, this comprehensive analysis provides insights into age-related attrition trends, gender disparities, marital status influences, and the impact of educational fields on employee departures within the organization.

TURNOVER ANALYSIS
The analysis reveals that the overall attrition rate is higher for male employees (150) compared to their female counterparts (87). Notably, within the male gender, those occupying Laboratory Technician roles contribute significantly, constituting 19.41% of the total attrition.

The Average Total Attrition is higher for males (16.67) compared to females (9.67). The most substantial divergence in Total Attrition between males and females occurs in the Laboratory Technician role, with males exceeding females by 30.

Examining departmental attrition, the Research & Development department records the highest Total Attrition at 133, followed by Sales at 92 and Human Resources at 12. Remarkably, Research & Development contributes to 56.12% of the overall Total Attrition.

Further analysis reveals that employees with less than a year in their current role, particularly within the Research and Development Department, experience the highest attrition count. Additionally, within the Sales department, employees with 2 years in their current role slightly outnumber those with less than a year (5 compared to 4).

In terms of travel patterns, employees who rarely travel (156) surpass the attrition count of those who travel frequently (69) and those who do not travel at all (12).

**TURNOVER ANALYSIS II**
Employees that got employed to an Entry level job role 143, depart the organization voluntarily or involuntarily mostly compared to those as Junior or associate 52, Mid-level specialist (32), Executive (5), Senior role (5)

The Managerial role stands out with the highest Average Monthly Income at 17,181.68, marking a substantial 554.29% difference from the Sales Representative role, which records the lowest Average Monthly Income at 2,626.00.

A negative correlation is observed between Average Monthly Income and the total Sum of Attrition Count. Laboratory Technicians accounted for 26.16% of the total Sum of Attrition Count.

The most notable divergence between Average Monthly Income and Sum of Attrition Count is observed in the Managerial role, where Average Monthly Income significantly surpasses the Sum of Attrition Count by 17,176.68.

Furthermore, the Average Sum of Attrition Count is higher for males (50) than females (29). The most significant discrepancy in Sum of Attrition Count between males and females occurs in the 31-45 age group, with males exceeding females by 31.

Employees with Low performance (200) exhibit a higher Sum of Attrition Count than those with high performance (37). Notably, employees who do not engage in overtime have a lower attrition count (110) compared to their counterparts who participate in overtime (127).

Additionally, employees entering the organization in Entry-level roles (143) are more likely to experience voluntary or involuntary departure compared to those in Junior or Associate roles (52), Mid-level Specialist roles (32), Executive roles (5), and Senior roles (5).

This in-depth analysis provides valuable insights into the nuanced relationships between income levels, job roles, gender, age groups, performance, overtime engagement, and their impact on employee attrition.

**EMPLOYEE WELLNESS**
The analysis reveals that employees enjoying a Good work-life balance exhibited the highest Sum of Attrition Count at 127, surpassing those with Average, Excellent, and Bad work-life balances. Notably, Good work-life balance constituted 53.59% of the total Sum of Attrition Count.

In terms of Job Involvement, employees with moderate involvement recorded the highest Sum of Attrition Count at 125, marking an 861.54% increase compared to those with high job involvement, who exhibited the lowest Sum of Attrition Count at 13. This pattern persisted across all four Job Involvement categories, where Sum of Attrition Count ranged from 13 to 125.

Furthermore, the analysis highlights a departure trend among employees based on their satisfaction levels. Employees satisfied with their relationship (71) demonstrated a higher attrition count compared to those very satisfied (64), Dissatisfied (57), and very dissatisfied (45).

In the context of job satisfaction, employees content with their job (73) displayed the highest attrition count, contrasting with those very dissatisfied (66), very satisfied (52), and dissatisfied (46).

This nuanced examination underscores the intricate interplay of work-life balance, job involvement, relationship satisfaction, and job satisfaction in influencing employee attrition within the organization.
