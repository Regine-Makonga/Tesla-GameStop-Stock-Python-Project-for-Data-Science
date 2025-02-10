# Tesla-GameStop-Stock/Revenue-Analysis
## Analyzing Historical Stock/Revenue Data and Building a Dashboard
In this Project we will use yfinance and  Webscraping to extract the revenue data for Tesla from 2010 to 2022 and GameStop from 2006 to 2020  and build a dashboard to compare the price of the stock vs the revenue. Extracting essential data from a dataset and displaying it is a necessary part of data science; therefore individuals can make correct decisions based on the data. 
- For Tesla stock data Webscraping Extraction we user the [webpage](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)

- For GameStop stock data Webscraping Extraction we user the [webpage](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html))
## Table of Contents
- [Use of yfinance to Extract Tesla Stock Data](#Use-of-yfinance-to-Extract-Tesla-Stock-Data)
- [Use of Webscraping to Extract Tesla Revenue Data](#Use-of-Webscraping-to-Extract-Tesla-Revenue-Data)
- [Use of yfinance to Extract GME Stock Data](#Use-of-yfinance-to-Extract-GME-Stock-Data)
- [Use of Webscraping to Extract GME Revenue Data](#Use-of-Webscraping-to-Extract-GME-Revenue-Data)
- [Plot Tesla Stock Graph](#Plot-Tesla-Stock-Graph)
- [Plot GameStop Stock Graph](#Plot-GameStop-Stock-Graph)
- [Access the files](#access-the-files)
- [References](#references)
## Data Analysis

Data Analysis involved exploring the clean LA Crime data, the process was carried out with SQL and  Python to answer a variety of key questions such as:
 - How many crimes are occurred per month?
 - How many crimes are occurred per year?
 - How many crimes are occurred per Age?
 - How many crimes are occurred Over Time (Year and Month)?
 - What is the most common type of crime based on crimedescription ('Crm Cd Desc') in each area ?
 - How does the time of occurrence relate to the type of crime? Are certain crimes more likely at certain times of day?
 - What is the average age of victims for each type of crime?
 - Are men, women, or others sex more likely to be victims of certain types of crimes?
 - Which area has the most crimes?
## Data Visualization
The data visualization process was carried out with Python by creating plots and dashboard to visualize the results obtained from the data analysis process.

Here are some graphs and dashboard:

#### Dashboard
<img width="427" alt="LA Crime Dashboard" src="https://github.com/user-attachments/assets/d1f694db-e3eb-4bb9-aa13-7120739fc186" />



#### Plots
<img width="470" alt="Crime per Month" src="https://github.com/user-attachments/assets/514c13ce-d7b8-4453-9565-0b5590cf0fe3" />

<img width="462" alt="Crime per Year" src="https://github.com/user-attachments/assets/b8eac637-3de9-4111-b43d-1f8ee13a92f4" />

<img width="645" alt="Most Common type of Crime per Area" src="https://github.com/user-attachments/assets/28b6ddef-414b-4f1f-975c-838c8cf45626" />

<img width="643" alt="Crime frequency by time period" src="https://github.com/user-attachments/assets/86f7e265-c976-43fc-bec3-803ac645d4b5" />
<img width="557" alt="Victim sex by crime type" src="https://github.com/user-attachments/assets/617adb85-3122-4dae-ae1d-91579ec95816" />

 

## Access the files
 - To run the project, make sure you have installed  SQL to perform analysis, and Python with pandas, seaborn, matplotlib for data analysis and data visualization.
 - Download the LA Crime dataset which hasn't been included in the repository due to its large size you can Download it from [data.lacity.org](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data).
 - Using python in jupyter notebook to perform data cleaning and data Preparation then export data for data analysis 
 - Create a database in MySQL Workbench, create table, load clean and prepared export from python and follow the queries in [data_analysis.sql](LACrime_Data_Analysis.sql) then perform the analysis.
 - For the data visualizations use the [visualizations.ipynb](LACrime_Analysis_Visualization.ipynb) you can use it on python in jupyter notebook 

## References
[Databases-and-SQL-for-Data -cience-with-Python](https://www.coursera.org/learn/sql-data-science/home/module/1) IBM certificate


[Data-Visualization-with-Python](https://www.coursera.org/learn/python-for-data-visualization) IBM certificate


[Pandas.pydata.org](https://pandas.pydata.org/docs/user_guide/index.html)


[Matplotlib.org](https://matplotlib.org/stable/users/index.html)


[seaborn.pydata.org](https://seaborn.pydata.org/)



   







   


