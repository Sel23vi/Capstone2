# Capstone2
The Phonepe pulse Github repository contains a large amount of data related to various metrics and statistics. The goal is to extract this data and process it to obtain insights and information that can be visualized in a user-friendly manner.

Technology Stack Used:
1.	Python
2.	MySQL
3.	Streamlit
4.	Github Cloning
5.	Geo Visualisation
6.	Dynamic Updation
   
Approach:
1.	Clone the GitHub Repository & Download Geojson file:
•	First, clone the PhonePe Pulse GitHub repository using Git Bash or any other suitable tool. https://github.com/PhonePe/pulse
•	Use the following syntax to clone the repository into your local drive:
from git.repo.base import Repo
Repo.clone_from("GitHub Clone URL", "Path to get the cloned files")
•	Download a proper Geojson file containing geospatial information like shapefile and spatial geometry co-ordinates, will suit your purpose. https://gadm.org/download_country.html

2.	Data Extraction:
•	After cloning the repository, you’ll have access to the data files.
•	Use scripting to fetch the data present from the PhonePe Pulse GitHub repository and store it in a suitable format, such as JSON.
•	The extracted data will be used for further analysis and visualization.
3.	Data Transformation:
•	In this step, convert the JSON files available in the folders into a readable and understandable DataFrame format.
•	Iterate through each file and extract the required keys and values.
•	Create a DataFrame using libraries such as Pandas, os, and json. 

4.	Data Preprocessing: 
•	Once you have the data, preprocess it to clean and organize it for analysis. This may involve handling missing values, formatting dates, text styles, and converting data types as necessary to match the case and styling  and number of states and district names in your geojson file.
•	Iter through all the data sets available in the cloned repository and repeat the data transformation and preprocessing for every dataset.

5.	Data Storage:
•	Store/save the cleaned data as tables in the SQL database for interactive querying and dynamic visualization
•	Also save a copy as csv or excel or other suitable format for geo-spatial visualization.
•	Ensure appropriate scripts in place to periodically update database and reflect the latest data.
•	Also store a copy of the data, 

6.	Data Analysis: 
•	Perform exploratory data analysis (EDA) to understand the patterns and relationships in the data. This could include calculating summary statistics, identifying trends over time, and finding correlations between different metrics.

7.	Insights Generation: 
•	Use the results of your analysis to generate insights and information that are relevant to the problem statement. This could involve identifying key performance indicators (KPIs), detecting anomalies or outliers, and uncovering interesting trends or patterns.

8.	Data Visualization: 
•	Visualize your insights in a user-friendly manner using charts, graphs, and other visualization techniques. Choose visualizations that effectively communicate the information you want to convey to the intended audience.

9.	Dashboard Creation (Optional): 
•	If desired, create a dashboard or interactive interface to present the visualized data in a cohesive and interactive format. This could involve using tools like Tableau, Power BI, or custom-built web applications.

10.	Documentation: 
•	Document your analysis process, including the data sources, preprocessing steps, analysis techniques, and visualization choices. This documentation will be valuable for understanding and replicating your work in the future.
