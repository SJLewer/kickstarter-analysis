# Kickstarting with Excel

## Overview of Project

### Purpose: 
Analyze Kickstarter data to assess how different campaigns fared in
relationship to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Analysis is based on the number of Theater campaign outcomes (Successful, Failed, and Canceled) and the month they were launched. (Link to Data Source below)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90986041/133950820-ac7eb037-da10-4a75-820a-b3bdd0f2b5ba.png)

### Analysis of Outcomes Based on Goals
Analysis is based on the percentage of successful, failed, and canceled plays based on the funding amount goal. (Link to Data Source below)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90986041/133950817-f9b80830-7814-47bf-b614-e3eac8dd89df.png)

### Challenges and Difficulties Encountered: 
* FORMULA VALIDATION: While validating results of the COUNTIFS formulas, the total count of Fails did not 
  match the total from the filtered Kickerstarter data set.  I found the error in the "Greater than 50000" formula.  I forgot the "=" (>=50000).  
* GRAPH RESULTS: When I was reviewing the Outcomes Based on Goals graph, I noticed there weren't data points for "Less than 1000". 
  I discovered the data range did not include the first data row.

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
1. As shown in the "Theater Outcomes Based on Launch Date" graph, campaigns launched 
in May are the most successful. 
2. Campaigns launched in December have a 50-50 chance of success or failure.  
3. While no campaigns were canceled in October, it's one of the highest 
months for failure.

- **What can you conclude about the Outcomes based on Goals?**
1. As shown in the Outcomes Based on Goal graph, campaigns $1,000-4,999 and $35,000-44,999 are the 
most successful. 
2. Campaigns $25,000-29,999 and greater than $45,000 are the most likely to fail, with $45,000-49,000 failing 100% of the time.  
3. None of the campaigns were canceled based on their goal.

- **What are some limitations of this dataset?**  
1. Without performing statistical analyses, the conclusions are based on visual and "it-seems-like" 
feelings rather than unbiased conclusions based on calculations.
2. The Theater Outcomes analysis includes both plays and space subcategories.  The Outcomes Based 
on Goal analysis is limited to plays. Space campaigns may be skewing the Theater Outcome results. 
Therefore, the two analyses should not be used together without further alignment of the 	
underlying dataset.

- **What are some other possible tables and/or graphs that we could create?** 
1. A stacked bar chart would be a better representation of the Outcomes by Goal ranges. Line graphs
show a continous "journey" from one point to another (e.g., month-to-month), whereas bar charts show 
data sets in categories (Less than 1000, 1000-4999, etc.).
2. Statiscal analysis using a Box Plot with relationships of the mean, median, IQR, and outliers.
3. Pivot Charts with options to filter by subcategory (e.g., plays and space).
---
**Data Source:** [Kickstarter Challenge Data Set] https://github.com/SJLewer/kickstarter-analysis/blob/main/Kickstarter_Challenge_Submit_Copy.zip

**Analyst:** Sara Lewer
