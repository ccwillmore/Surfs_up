# Surfs_up  
  
### Overview of analysis  

The purpose of the analysis is to report summary temperatures statistics for Hawaii.  The temperature summaries will help to evaulate the potential of a proposed combination surf shop and ice cream shop.  
  
[June temperatures](June_temperature_statistics.png)  

[December temperatures](December_temperature_statistics.png)  

The temperature data were delivered as a SQLite database.  The database was reflected onto a database object.  The data were filtered by month, stored in pandas dataframes, and summary statistice were generated using pandas.describe().  
  
### Results  

Obversations from the temperature statistics:  

1. The average temperatures in the summer (June) and winter (December) are remarkably consistent.  The mean in June is 75 degrees Farenheit.  The mean in December is 71 degrees farenheit.
2. The temperature in December is more variable than in June (Standard deviation 3.26 in June vs 3.75 degrees in December).  
3. There is the possibility for a relatively cold day in December but the minimum (56 degrees Farenheit) is a statistical outlier (more than 3*STD from mean).  
  
### Summary  

Additional statistical analyses could help to shed light on the weather conditions in June and December.  

1. Summary statistics on the amount of precipitation could help to understand if there will be enough surfers in June or December to justify investing in the surf / ice cream shop.  More precipitation in December and generally less stable weather could limit tourism and profits.  

2. Plotting daily temperatures and precipitation for both months could help to better understand the data.  Is the weather really less stable and predictable in December or is there one week that has poor weather while the rest of December has beautifful weather for surfing and ice cream?
