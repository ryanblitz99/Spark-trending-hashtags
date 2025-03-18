Using Apache spark and spark SQL, we create a structured streaming application, select a random line of data at a time from the JSON file and feed it into a dataframe. 
We then convert the dataframe into a spark sql table where we can run sql commands to manipulate and extract the most popular hashtags by count.
