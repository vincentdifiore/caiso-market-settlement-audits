# caiso-market-settlement-audits
Audit Analysis with Synthetic Grid Data by Vince DiFiore

# Context

From reviewing online sources such as CAISO's OASIS, I was able to create a mock dataset of Schedules, Prices, Meter Data, and Locations. While large data taken from the grid would still work with these queries, using a mock dataset streamlined the analysis concepts for my purposes. Within these tables, there are general fields that one would find pertaining to Ids, interval timing, megawatts, and other metrics that the grid and CAISO account for.

By analyzing data fields among the tables, I was able to create a new and useful table, "Full Settlement Audit View". From here, I created several other queries that returned a table to display metrics or to highlight NULL values. 

CAISO Settlement Audits is a full review of the SQL code used. to create tables, insert data, and query the tables for analysis. 

The attached CSV files are audit tables created in the analysis. The audits used to detect NULL values did not display data (no NULL values in this project).


