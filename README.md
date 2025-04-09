# caiso-market-settlement-audits
Audit Analysis with Synthetic Grid Data by Vince DiFiore

# Context

From reviewing online sources such as CAISO's OASIS, I was able to create a mock dataset of Schedules, Prices, Meter Data, and Locations. While large data taken from the grid would still work with these queries, using a mock dataset streamlined the analysis concepts for my purposes. Within these tables, there are general fields that one would find pertaining to Ids, interval timing, megawatts, and other metrics that the grid and CAISO account for.

By analyzing data fields among the tables, I was able to create a new and useful table, "Full Settlement Audit View". From here, I created several other queries that returned a table to display metrics or to highlight NULL values. 


