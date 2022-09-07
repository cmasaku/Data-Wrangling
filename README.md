# Data-Wrangling
### Introduction
There are 3 datasets that are not clean. The purpose of this excercise is to wrangle the data. The data wrangling process includes 3 steps:Gather, Assess and clean. 
My first step was gathering data. I gathered 3 datasets. My datasets are assigned df1 for the twitter-archive-enhanced.csv ,df2 for the image-predictions.tsv and df3 for the tweet-json.txt. 
Before assessing my data, I created a copy of each of the datasets so as to keep a copy of the original unclean data.

I then assessed all the 3 datasets separately to identify any quality issues and any tidiness issues.
These were the main issues I found, both visually and programmatically.

### Quality issues
1.Identify and drop rows which are retweets-Use the 'retweeted_status_id' column.

2.Missing values in 'in_reply_to_status_id','in_reply_to_user_id','retweeted_status_user_id','retweeted_status_timestamp'

3.Name of dog column has 745 missing values(stored as none). Some names are also stored as "a","an","the","quite","officially", etc. All lower case names are invalid.

4.Wrong data type for 'timestamp' column in df1


#### tweet-json table

5.Missing values in 'geo', 'coordinates', 'place', 'contributors', 'in_reply_to_status_id','in_reply_to_status_id_str',
'in_reply_to_user_id', 'in_reply_to_user_id_str','in_reply_to_screen_name', ''retweeted_status','quoted_status_id', 'quoted_status_id_str', 'quoted_status'.

6.Columns with same value in all rows-'possibly_sensitive','possibly_sensitive_appealable'.

7.Incorrect datatype for 'created_at' column in df3

8.Renaming the id column in df3 to tweet_id

### Tidiness issues
1.Multiple dog stages columns-floofer,pupper,puppo,doggo

2.All the 3 datasets are part of same observational unit.


-After assessing and identifying these quality and tidiness issues, I then cleaned the highligted issues.

-Stored the cleaned master dataset to a CSV file named "twitter_archive_master.csv".

-Analysed and visualized the data giving 3 insights.

### Conclusion
The dataframes could be having more than the issues highlighted above, however the key areas have been cleaned and merged into 1 dataframe ready for further analysis