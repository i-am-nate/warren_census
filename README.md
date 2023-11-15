# warren_census
A comparison of Warren public US Census survey data compared to Macomb County and to Michigan across 10 years (2011 and 2021).

Attached here are a few .csv files and a .zip file containing the visuals associated with this combined dataset. To view everything in one spot, [here is the link](https://docs.google.com/spreadsheets/d/1wOJMW_ut2TIKjMk5yDdE2o7tYk8X7kE1BSzvrFA80k0/edit?usp=sharing) to the Google Sheets where it is all laid out there.

'raw.csv' is the resulting imported .csv file from the initial SQL 'join' of the 6 databases. That query was performed within public datasets using BigQuery, and a screenshot of that query is attached (sql.png).

'cleaned.csv' represents the data cleaned version of the data (also translated into long instead of wide data).

The remaining 5 .pdf files are exported from the Google Sheet and represent subsets of various data points from the full 'cleaned.csv': comparing races, education, population, commutes, and vehicles.

Visualizations and key takeaways are included within each .pdf and are the same as what lies within the Google Sheet.
