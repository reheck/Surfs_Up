# Surfs_Up
## Overview
### W. Avy, an interested investor for an ice cream and surf shop on Oahu, Hawaii, has asked for descriptive statistics for temperature observations in June and December from 2010 to 2017. These statistics will help him determine if the venture will succeed year round. Utilizing a SQLite database of Hawaii weather data, SQLalchemy, and Python, the data for June and December was filtered and descriptive statistics performed on the resulting dataframe.
## Results
### While the June and December statistics were very similar, there are three notable differences:

December 2010-2017 Temperature Stats

![image](https://user-images.githubusercontent.com/102757676/170047075-dcd0f87b-efc5-4884-9d52-49d8de2d557c.png)

June 2010-2017 Temperature Stats

![image](https://user-images.githubusercontent.com/102757676/170047018-2e67f882-3ce7-4e1c-880e-f6c3cc7b6590.png)


### 1. The count of total observations in December is about 200 data points shorter than the June data. 
### 2. The average temperature in December is over 3 degrees cooler than in June. Compare the June mean temp of 74.9F to the December mean temp of 71.0F.
### 3. The coolest date in the month of December is nearly 8 degrees cooler than in June. Compare the June min temp of 64F and the December min temp of 56F.

## Summary
### From the June and December descriptive statistics, the temperature year-round is farily similar. Therefore, based solely on temperature, the surf and ice cream shop would succeed on Oahu, Hawaii year-round. 
### A recommended additional query to gather more weather data for June and December would be for the precipitation data. The more it rains, the less traffic on the beach. Another recommended query would be regarding wind speeds as they may relate to wave hights. Higher waves may mean more surfers especially experienced ones, but too many days of dangerously choppy water could mean fewer surf rentals as newbie surfers may abstain from attempting to surf in serious waves. If the data for storms could be gathered for June and December, that would also provide beneficial information. Dangerous storms keep surfers from the beach and thus from the surf and ice cream shop.
