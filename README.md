# An Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends

### Purpose
Louise's play *Fever* reached its fundraising goal in a short amount of time, which served as the basis for this final challenge. This analysis allows us to help Louise understand how different campaigns fared in relation to their launch dates and their funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To visualize how different campaigns fared in relation to their launch date, I created a pivot table that shows successful, failed, and canceled theater campaigns for each month. With this table, I created a line chart.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103080942/162129674-61a6cc24-8133-41ae-a479-9e07504edc47.png)

### Analysis of Outcomes Based on Goals
To visualize how different campaigns fared based on the funding goal amount, I first created a chart that shows the percentage of successful, canceled, and failed plays split out by goal range. And then, created a chart.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103080942/162129895-88b5ef60-9a3c-45da-afa1-924a23a6da67.png)


### Challenges and Difficulties Encountered
I did not have trouble with the Outcomes Based on Launch Date assignment, but it was the first time I have used the YEAR function so I used the BCS excel documentation link. 
The challenge I came across in the Outcomes Based on Goals activity was because the large size of the data. When calculating the “number canceled” column, I got 0 values for every row. Though I checked my formula for accuracy several times, I only used columns D and F to check my work, failing to scroll to the far right and compare column R. So, all along my formula was correct, but I spent hours troubleshooting on google thinking I messed up. Finally, I reached out to the AskBCS channel and they confirmed my answer. 

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
The Theater Outcomes by Launch Date chart lets us know that May was the most common launch month for successful play campaigns with a total of 111 successful campaigns. Additionally, December was a very unpopular month to launch campaigns.

- **What can you conclude about the Outcomes based on Goals?** Campaigns with the high goal range of $45,000 to $50,000 were the least successful– 0 campaigns were successful with that goal range.

- **What are some limitations of this dataset?** The lack of information on backers is one limitation to the dataset. If we understood what types of backers (i.e. demographic information) support different campaigns, we could help Louise understand if successful campaigns attract the general population as a whole, or certain subgroups in particular.

- **What are some other possible tables and/or graphs that we could create?** Based on the information the dataset provides, we could create a table and graph to see how goal amounts vary by country. We could also create a table and graph to visualize how different campaign category might influence the number of backers.
