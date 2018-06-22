*Google Cloud BigQuery Part :

I downloaded the CSV File for Popular Tweets in My Country Egypt using my Twitter API on my Personal Twitter Account .
Upload the CSV Data File for the Tweets on Google Cloud BigQuery for Storage (i made a job to write the Result Files on Google BigQuery but it failed so i skiped this part , and used my Bucket Instead on Google Cloud Platform)   
It Detected the Scheme and Created the Table based on this CSV File .
I can Query on this Data using SQL Scripts to view Data like:

Select * from [Twitter.Twitter_UserTweets] --This is the Main CSV File that i used on ETL DataFlow, Storage and Google DataStudio  
Select * from [Twitter.Twitter_t]  

Note :
I tried to share the BigQuery Part and DataSet with Everyone and get a link but i couldn't
Thanks to Provide account to add him to View this Part