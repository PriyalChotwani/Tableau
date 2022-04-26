# Tableau
Tableau is used to draw insights and create dashboards from 2 datasets. First is the World Bank CO2 data and the second is the GBI dataset.

## About Tableau

Tableau was founded in 2003 which has been aimed to improve the data analysis and data accessibility through visualizations (Tableau, 2022). It has become a powerful and fastest growing tool and is leading in the market because of its platform which makes it easier for people to explore, manage, and modify their data to create informative and insightful visuals. It is gaining its popularity has a large fan base in public and enterprise as it is simple, fast, user-friendly, easy to learn, and can be used to create very interactive dashboards. I chose this tool to include in my portfolio because of its popularity and I’ve always wanted to learn briefly about this tool. Following are the key capabilities of this tool (KnowledgeHut, 2019):

 - It is a free tool which has remarkable visualization capabilities. It is a high performing tool which helps in converting statistical information into comprehensible logical results which are also very visually appealing.
 - It makes the task of transforming the data by creating new fields or pivoting the table very easy. It provides various functionalities by which the user can easily manipulate the data
 - It is a robust and reliable tool even for large datasets.
 - It allows the users to have multiple data sources such as HADOOP, Excel, CSV, Database technologies, and many more.
 - It has built a very strong community and has various forums where users share their experiences and support each other by resolving the queries.
 - The distinguishable factor is that it is also mobile-friendly and supports full functionality that a desktop and online version has.

## Dataset and Research questions

Tableau will be used to draw insights and create dashboards from 2 datasets. First is the World Bank CO2 data which contains the information of each Country and their CO2 per capita emissions on a yearly basis. Second is the GBI dataset in which the data is stored in an excel file with 132,760 rows from 2007 to 2016. It contains the information about an organization with column names: year, month, date, product description, customer description, city, and many more. First these datasets are imported in Tableau (Public) and for GBI dataset, the data type of Order Number, Year, and Month is changed to string to perform the data visualizations. GBI dataset is very limited in terms of countries as it only covers US and Germany, also the information about each country and its cities is not complete to do deeper analysis. But it is perfect to answer the following questions and obtain the information about the revenue generated and sales of the products.

Following are the questions that will be answered using World Bank CO2 dataset:

 - Create a dashboard to show CO2 emissions by Countries since 1960 via Geo Graph and Line Graph.
 
Following are the questions that will be answered using GBI dataset:

 - Compare Average Revenue (in USD) and Average Gross Margin for US and Germany for all the years.
 - Compare the Gross Margin Ratio of each division for all the years.
 - Which city of Germany has highest Sales Quantity?
 - Create a dashboard to compare top 5 Products in terms of Sales Quantity during 2016 and their Gross Margin and top 5 Products in terms of Gross Margin during 2016 and their Sales Quantity. Are the Products same for both the graphs?

## Applying the Analytical Tool and Results

##### Question 1: Create a dashboard using World Bank CO2 to show CO2 emissions by Countries since 1960 via Geo Graph and Line Graph.
The following figure represents a dashboard where 2 types of graphs are shown i.e., Geo Graph and Line Graph. For the Geo Graph, Longitude is dropped into columns, Latitude into rows, Country Name into detail, CO2 per Capita into size and color after selecting the measure to be average. As it is visible from the graph, Qatar has the highest average CO2 per capita i.e., 54.42. Also, this graph helps in identifying the average CO2 per capita of any country just by hovering over the graph. Line graph points towards the trends of CO2 emission of each country from 1960 to 2012. Qatar seems to be the country which has highest CO2 emissions over the years. Few countries like Kuwait, UAE and others had a higher CO2 emission in the beginning, but it got declined as the years passed.
![Alt text](Images/TableauQ1)

##### Question 2: Compare average revenue (in USD) and average gross margin for US and Germany for all the years.
Following Figure depicts a line graph where x-axis is year and y-axis represent the values where orange line shows Average Revenue (USD) and blue line shows Average Gross Margin (USD). Gross Margin is a calculated field which has been created by using the formula: Revenue (USD) – Discount (USD) – Costs (USD). Both the lines are coherent to each other and follow similar trend as both the fields are directly related to each other (higher the revenue, higher the gross margin). It is notable that overall Germany has higher revenue than US and both the countries have followed a non-consistent upward trend.
![Alt text](Images/TableauQ2)

##### Question 3: Compare the Gross Margin Ratio of each division for all the years.
Figure shows a column chart where y-axis represent Gross Margin Ratio, x-axis represent year and color represent the divisions. Blue color represents AS while orange represents BI. Gross Margin Ratio is a calculated field which has the formula: Gross Margin USD/ (Revenue USD – Discount USD). The graph suggests that AS has higher gross margin in comparison to BI in all the years. 2008 has the highest GMR for BI, while 2016 has the highest for AS. Altogether, both the divisions show a similar trend with only slight differences.
![Alt text](Images/TableauQ3)

##### Question 4: Which city of Germany has highest Sales Quantity?
Figure shows a Geo Graph where color represents the sum of Sales Quantity in all the cities of Germany. According to the following visualization, München has highest Sales Quantity i.e. 66,955 while the lowest is for Anklam i.e. 13,496.
![Alt text](Images/TableauQ4)

##### Question 5: Create a dashboard to compare top 5 Products in terms of Sales Quantity during 2016 and their Gross Margin and top 5 Products in terms of Gross Margin during 2016 and their Sales Quantity. Are the Products same for both the graphs?
The following dashboard represents to column charts where x-axis is Products and y-axis shows the values for both Sales Quantity (represented by orange color) and Gross Margin (represented by purple color) respectively. Top 5 products with highest Sales Quantity are: Air Pump, Road Bike Alu Shimano, Water Bottle Cage, Men's Off Road Bike Hard Tail SRAM, and Men's Off-Road Bike Fully. Whereas top 5 products with highest Gross Margin are: Professional Touring Bike-Silver, Deluxe Touring Bike-Silver, Road Bike Carbon Shimano, Men's Off-Road Bike Fully, and Men's Off Road Bike Hard Tail SRAM. This suggests that there is no correlation between sales quantity and gross margin, therefore the products that have high sales quantity may or may not have high gross margin and vice versa.
![Alt text](Images/TableauQ5)

## Analysis and Critique of the Tool

Tableau is a tool which nowadays is must to know to better understand and learn about the data and present the data insights in the form of informative and appealing graphs. It is a freely available tool which can be even used by non-developers as efficiently as people who know coding. It has even built a supportive community where everyone comes forward to share their experiences in the form of appealing and insightful dashboards. It is well suited for large datasets and helps in drilling down the data and summarizing it as per the requirements of data analysts. Also, Tableau enables the users to ask the questions about the data in simple English and further perform the Natural Language Processing algorithms to interpret the data and fetch the results. This feature comes in handy for fast factual checks and to the point results.

The features offered by this tool are vast, but in my opinion, there is a room for improvement as Artificial Intelligence and Business Intelligence can help a lot in learning and analysing the data which is not being offered fully in this tool yet. But as continuous improvements and updates are going on, I have full faith in this tool. I believe that there is a long learning curve with Tableau as it offers many functionalities, which can only be used to its full potential after continuous practice and learning.

## Conclusion:
Overall, this is an amazing tool, and it makes working with complex and large datasets fun. It is highly gaining popularity from everyone who is passionate about learning about the data and presenting the story in a visually appealing manner, as well as make important decisions by deriving the information from the datasets. Unlike other tools Tableau is not hardware dependent and it can be run on all kinds of operating system which makes it available for a larger audience. I personally had fun working on my data with this tool and I would recommend this to everyone who want to be a data analyst.
