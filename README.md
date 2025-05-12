# CAISO Market Settlement Audits
Audit Analysis with Synthetic Grid Data by Vince DiFiore

# Context

"The California Independent System Operator (ISO) manages the flow of electricity across the high-voltage, long-distance power lines that make up 80 percent of California's power grid...As the impartial grid operator, the California ISO opens access to the wholesale power market that is designed to diversify resources and lower prices. It also grants equal access to 25,865 circuit-miles of power lines and reduces barriers to diverse resources competing to bring power to customers... California ISO operates independently—managing the electron traffic on a power grid we do not own—making sure electricity is safely delivered to utilities and consumers on time and reliably." - CAISO website

From reviewing online sources such as CAISO's OASIS, I was able to generate a mock dataset of Schedules, Prices, Meter Data, and Locations. Using a mock dataset streamlined the fields, data, and analysis concepts for my purposes. Within these tables, there are general fields that one would find pertaining to Ids, interval timing, megawatts, and other metrics that the grid and CAISO account for.

By analyzing data fields among the tables, I was able to create a new and useful table, "Full Settlement Audit View". From here, I created several other queries that returned tables to display metrics and highlight inaccuracies. 

_CAISO Settlement Audits_ contains the SQL code used to create tables, insert data, and query the tables for analysis. 

The attached CSV files are audit tables created in the analysis. The audits used to detect NULL values did not display data (no NULL values in this project).

Ultimately, this project is a demonstration of how query analysis with basic calculations can identify ineffiencies in timing, energy distribution, and pricing in the grid. By reducing these inefficiencies, power can be delivered to homes and businesses more timely, with more accuracy, and therefore with less cost impact. 

Relevant concepts: Business Logic, Root-Cause Analysis, Actual vs Expected Payments, Unplanned Injections, Scheduling Deviations, Imbalance Costs, Energy Delivery


