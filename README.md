The initial DunnHumby dataset contains- 

* household level transactions over two years for a group of 800 households who are frequent shoppers.
* All of a household’s purchases within the store, not just those from a limited number of categories.
* Geographic details of the stores were obtained from a SQL Server.


1) The file "Data Modelling.pbix" contains all the data cleaning and transforming operations done using DAX-
   * This includes obtaining the necessary data.
   * Forming a star schema with fact table and dimenision tables.
   * Collecting additional data that the users might need for analysis.
  
2) "Marketing Analysis.pbix" contains the modified data model from the "Data modelling" file, our focus here is to create measures to find out if there is any evidence to suggest that marketing/prmotional efforts improve overall customer spending. Some important aspects of it- 
    * Obtaining additional data collected during the promotional campaigns and incorporationg it into the existing data model.
    * Conducting promotional analysis for the products that were promoted, in store or through mailers. KPIs such as Promotional Effectiveness and Weekly Promotion Sales.
    * Conducting Campaign analysis for direct marketing efforts.
  
3) "Dashboards.pbix" you will find an interactive dashboard of the same data. It contains important KPIs for sales analysis such as Year-to-date sales by state compared with previous year, Sales by hour of day/day of week and many more.


![Dashboard](images/1.png)
![Department Details](images/2.png)


Thank you.
