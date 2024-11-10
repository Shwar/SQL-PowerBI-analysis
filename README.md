# SQL-PowerBI-analysis with SQL and Dashboard report with PowerBI


## Overview
This project contains a Power BI dashboard built to analyze and visualize data from Awesome Chocolate. The dashboard provides insights into   sales trend, Sales by Geographical regions, Number of boxes etc.

The project includes the `.pbix` Power BI report file, SQL files for awesome chocolates dataset and another sql file for  analysis. This repository is intended for sharing and version control of the Power BI dashboard.

## Files Included
- `PowerBI and SQL.pbix`: The main Power BI report file.
- `awesome-chocolates-data.sql`: File containing scripts to query and generate awesome chocolate dataset  used in the report.
  - `Sql script`: Sample queries for analysis.
- `README.md`: Documentation for the project.


## Setup Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone  https://github.com/Shwar/SQL-PowerBI-analysis.git


2. Open  MYSQL Workbench
   + Launch MYSQL workbench
   + Create a database - awesome chocolates
   + Create a new script
   + Copy and paste awesome-chocolates-data.sql file and execute the script
     
3.  Data Loading
   + Copy and paste the sql script file and excecute query by query for analysis
   + Practice ,practice to familiarize with the database and the tables
     
4.  Open PowerBI desktop
   + Launch PowerBi desktop application
   + Go to the **Home** tab and click **Get Data** .
   + Select ODBC or OLE DB and choose your MySQL connection.
   + Enter the connection details for your MySQL server.
   + Select the Awesome Chocolates database and load the necessary tables into Power BI.
   + The data should now be available for visualization in Power BI.


5. Create measures
   + Create measures in Report view pane and create neccessary dashboard

6. Publish
   
   + After being satisfied with your dashboard you can publish it to your service workspace and start sharing out
     
## Features
+ Data visualizations for chocolate sales, inventory levels, and customer demographics.
+ Custom filters and DAX for product names and measures management.
+ Real-time connection to the MySQL database for up-to-date reporting.

## Visualizations
- **Input PID in the parameters**:
- ![PID = P22](images/ChangePID.png)

- **Query Overview after PID input**:
-  ![PID = P22](images/PIDOverview.png)

  - **Dashboard overview**:
  -   ![PID = P22](images/dashboard1.png)

  - **When Product is updated - refresh on the dashboard to update the visuals**:
  -     ![PID = P22](images/refresh.png)
    
  - **When Product is updated and visual refreshed - the view of another Product trend**:
  -     ![PID = P22](images/dashboard2.png)


## Contributing

If you would like to contribute to this project, feel free to fork the repository, make changes, and create a pull request. Ensure any changes made are well documented in the comments or the README.

## Acknowledgements
Special thanks to Chandoo who provided the sql script to generate dataset
      
     
     
     
  

     


   
