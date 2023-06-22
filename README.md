# Projects with Microsoft Power BI Desktop

## Adventure Works Report Project - follow-along project

### Credits

The Adventure Works project was prepared with the guidance of Chris Dutton, Founder of Maven Analytics (https://mavenanalytics.io/) and Instructor Instructor of the course Microsoft Power BI Desktop for Business Intelligence at Udemy.

### Scope

The role of Lead Business Intelligence Analyst for Adventure Works Cycles, a global manufacturing company was mimicked for this project.

The goal of this analysis was to design and deliver a professional-quality, end-to-end business intelligence solution for the company, with Power BI and a raw csv files.

To see an overview of the report, please have a look at the pdf file AdventureWorks_Report or at the screenshots of the report in the folder, in case the PowerBI file won't work properly.


## Maven Market Project Report - indipendent project

### Credits

The Maven Market project was prepared from the base of the instructions of Chris Dutton, Founder of Maven Analytics (https://mavenanalytics.io/) and Instructor Instructor of the course Microsoft Power BI Desktop for Business Intelligence at Udemy.

### Scope

The role of Lead Business Intelligence Analyst for Adventure Works Cycles, a multi-national grocery chain with locations in Canada, Mexico and the United States, was mimicked for this project.

The goal of this analysis was to design and deliver a professional-quality, end-to-end business intelligence solution for the company, with Power BI and a raw csv files.

To see an overview of the report, please have a look at the pdf file MavenMarket_Report or at the screenshots of the report in the folder, in case the PowerBI file won't work properly.

## Adventure Works report
### SQL querying and connection to a data warehouse in SQL Server to Power BI

The report uses the open-source data warehouse AdventureWork, downloaded from the following address https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2022.bak.
This was uploaded to SQL Server, and here the needed VIEWS were created, in order to gather the necessary data for the following analysis.

Once, the data was ready (SQLQuery_to_BI.sql), a connection to Power BI through the local server of SQL server was created and the data was uploaded.
No heavy transformations were necessary for the power query.
Finally, the analysis of data was created through the calculation of measures and the creation of pages of the report.

##### NOTE

In order to be able to reproduce the analysis from the Power BI file, first the SQL code should be run on the local SQL server and create a different connection with the local SQL server and PowerBI.
