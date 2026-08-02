# SampleDynamicKPICard

The following is a sample dynamic and interactive KPI card.  It has 3 slicers.  One for the time period.  One to choose between the metric (New followers, Total Engagements, Total Impressions) and the end user can change the Moving Average that is used in the line chart of the visual below (3 days, 7 days, 14 days and 30 days).  

The KPI card also calculates the sum of the data based on the filter context as well as the delta versus the previous period for the time selected.  

For example, if the user chooses 'Total Engagements' and the 1M (1 month slicer), it will return 4.37K of total engagements for the time period of July 11th thru August 11th. 

It will also return the delta versus the previous 1 month period (June 11th to July 11th).  In this case it will show the delta in Total Engagements (+0.2K) and the % delta (4.6%)

And at the bottom of the KPI card is a combo column and line chart showing the impressions over the timeframe as well as the moving average (line chart) based on whatever moving average the stakeholder selects.

This allows the stakeholder to have a dynamic snapshot of different metrics in comparison to previous time periods and a visual to identify a trend in the data
