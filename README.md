# Udacity_Data_Wrangling_Project

 

### Quality issues
The names of the dogs in P1, P2 and P3 are not consistent, some start with Capital letter and some with small letter in df_predict

Expanded_urls has 59 missing values.There are lot of missing values in retweeted_status_user_id, retweeted_status_id, retweeted_status_timestamp, in_reply_to_status_id and in_reply_to_user_id in df_dogs

Use of '_' instead of space in p1, p2 and p3

Timestamp data type is object instead of datetime in df_dogs

tweet_id data type is integer instead of string in all the data

Some names are not written correctly in df_dogs such as 'a', 'quite', etc.

Missing values are represented differently, some as NaN and some as None

Column names in df_predict are not descriptive

Tidiness issues
Merge clean_df_dogs table with clean_df_more_data.

columns floofer, doggy, pupper and puppo in df_dogs shows different sizes of dogs, it should be merged into a column.
